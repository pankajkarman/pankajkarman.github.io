<html>
   <head>
	<meta charset='utf-8'>
	<title> Earth threejs </title>
	<style>	   
	   body { margin: 0; background-color: black;}
	   canvas { width: 100%; height: 100% }	
	</style>
   </head>
   
   <body>
  	<script src="/js/three.min.js"></script>
  	<script src="/js/orbit_controls.js"></script>
  	<script>
		var mapUrl = "/images/earth/earth_texture.jpg";
		const fov = 45;
		const width = window.innerWidth;
		const height = window.innerHeight;
		const nfield = 0.1;
		const ffield = 1000;
		const mrad = 25;	       
		
		const loader = new THREE.TextureLoader();
		var scene = new THREE.Scene();
		var camera = new THREE.PerspectiveCamera(30, width / height, nfield, ffield);
		
		var light = new THREE.AmbientLight( 0x888888 )
		scene.add( light )

		var light = new THREE.DirectionalLight( 0xfdfcf0, 1 )
		light.position.set(10,10,10)
		scene.add( light )
	  		  		
	    var geometry = new THREE.SphereGeometry(6, 50, 50);  
	    var material = new THREE.MeshBasicMaterial({
      		map: new loader.load(mapUrl),
      		bumpMap : new loader.load("/images/earthbump1k.jpg"),
      		bumpScale : 0.75,
      		color: 0xaaaaaa, 
      		specular: 0x333333,
      		shininess: 25
	      	});
  		  	  				
  		var earth = new THREE.Mesh(geometry, material);
  		scene.add(earth);
  		
  		//Clouds
		var cloudGeometry = new THREE.SphereGeometry(6.1,  50, 50);
		var cloudMaterial = new THREE.MeshBasicMaterial({
		  map: new loader.load("/images/earth/clouds.jpg"),
		  transparent: true,
		  opacity: 0.1
		});
		var clouds = new THREE.Mesh(cloudGeometry, cloudMaterial);
		scene.add(clouds);
		
		//Starfield
		var starGeometry = new THREE.SphereGeometry(100, 50, 50);
		var starMaterial = new THREE.MeshPhongMaterial({
		  map: new loader.load("/images/earth/galaxy_starfield.png"),
		  side: THREE.DoubleSide,
		  shininess: 0
		});
		var starField = new THREE.Mesh(starGeometry, starMaterial);
		scene.add(starField);
		
		//Moon 
		var moonGeometry = new THREE.SphereGeometry(2.5, 50, 50);
		var moonMaterial = new THREE.MeshPhongMaterial({
		  map: new loader.load("/images/earth/moon_texture.jpg"),
		  color: 0xaaaaaa, 
		});
		var moon = new THREE.Mesh(moonGeometry, moonMaterial);
		moon.position.set(mrad,0,0);
		scene.add(moon);
  		
  		camera.position.z = 25;
  		earth.rotation.x = 0.4;
  		
  		var renderer = new THREE.WebGLRenderer({ antialias: true }); 		
  		renderer.setSize(width, height, false);
  		document.body.appendChild(renderer.domElement);
  		var orbit = new THREE.OrbitControls( camera, renderer.domElement )
  		
  		var r = mrad;
	    var theta = 0;
	    var dTheta = 2 * Math.PI / 1000;
	        
	        //Set position increments
		var dx = .01;
		var dy = -.01;
		var dz = -.05;


	    var earthVec = new THREE.Vector3(0,0,0);
  		
  		function render() {
	  		requestAnimationFrame( render );
	  		
	  		//earth.rotation.x += 0.1;
	  		earth.rotation.y += 0.0009;
	  		clouds.rotation.y += .00095;
	  		
	  		theta += dTheta;
			moon.position.x = r * Math.cos(theta);
			moon.position.z = r * Math.sin(theta);
			
			//Update the camera position
		    camera.position.x += dx;
		    camera.position.y += dy;
		    camera.position.z += dz;

		  	//Flyby reset
		 	if (camera.position.z < 0) {
		       	camera.position.set(45,mrad,70);
		  	}
			
			camera.lookAt(earthVec);
	  		
	  		renderer.render( scene, camera );
  		};	 
  		
  		render();
  	</script>
   </body>
</html>
