1	<!--
.. title: Projects
.. slug: projects
.. date: 2020-05-05 20:11:51 UTC+05:30
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text
.. has_math: true
-->

<style type="text/css">
p a{
  text-decoration: underline;
}

ol a{
  text-decoration: underline;
}

nav, article{
  text-decoration: none;
}
</style>

<h1 style="background-color: #ADD8E6; color:#A52A2A">Open source libraries</h1>

<div class="card-deck">
  <div class="card">
    <img class="card-img-top" src="/images/hytraj.png" alt="Card image cap" width="410" height="475">
    <div class="card-body">
      <h5 class="card-title" align="left"> <strong> HyTraj </strong></h5>
      <p class="card-text" align='justify'>A python package for trajectory modeling and analysis using <strong>HYSPLIT</strong>. It supports parallel generation of large number of air-parcel trajectories alongwith functionality to perform receptor modeling for air pollution sources analysis alongwith trajectory mining using various machine learning techniques.</p>
       <a href="https://github.com/pankajkarman/hytraj" class="btn btn-primary">Go to Project</a>
    </div>
  </div>
  
  <div class="card">
    <img class="card-img-top" src="/images/vortex.gif" alt="Card image cap" width="410" height="475">
    <div class="card-body">
     <p> <br/> </p>
      <h5 class="card-title"> <strong> PyVortex  </strong> </h5>
      <p class="card-text" align='justify'>A python package for polar vortex analysis.  It includes functions to calculate equivalent latitude and edge of polar vortex using Nash criteria (important for polar ozone hole studies).</p>
      <a href="https://github.com/pankajkarman/pyvortex" class="btn btn-primary">Go to Project</a>
    </div> 
  </div>
</div>
  
<br/>  

<div class="card-deck">
  <div class="card">
    <img class="card-img-top" src="/images/bias.png" alt="Card image cap" width="600" height="300">
    <div class="card-body">
      <h5 class="card-title" align="left"> <strong> Bias Correction </strong></h5>
      <p class="card-text" align='justify'>A python library to perform bias correction of datasets in order to remove cross-dataset biases. Implemented methods include quantile mapping, modified quantile mapping, scaled distribution mapping (both Gamma and Normal corrections).</p>
       <a href="https://github.com/pankajkarman/bias_correction" class="btn btn-primary">Go to Project</a>
    </div>
  </div>
  
  <div class="card">
    <img class="card-img-top" src="/images/sat.png" alt="Card image cap" width="600" height="250">
    <div class="card-body">
     <p> <br/> </p>
      <h5 class="card-title"> <strong> Satellite Data Processing </strong> </h5>
      <p class="card-text" align='justify'>A collection of python scripts to read and correct atmospheric composition profile data from various satellites (<a href="https://www.esa.int/Applications/Observing_the_Earth/Meteorological_missions/MetOp/About_GOME-2">GOME2</a>, <a href="https://mls.jpl.nasa.gov/">Aura-MLS</a>, <a href="https://www.ball.com/aerospace/programs/omps">OMPS</a>) like geopotential height, Temperature, ozone, water vapor, N<sub>2</sub>O, ClO and HNO<sub>3</sub>.</p>
      <a href="https://github.com/pankajkarman/satellite" class="btn btn-primary">Go to Project</a>
    </div> 
  </div>
</div>
  
<br/> 

<div class="card-deck">
  <div class="card">
    <img class="card-img-top" src="/images/lulc.png" alt="Card image cap" width="200" height="400">
    <div class="card-body">
      <h5 class="card-title" align="left"> <strong> Land Use Land Cover (LULC) classification </strong></h5>
      <p class="card-text" align='justify'>A collection of python scripts to perform LULC analysis using Google Earth Engine (GEE) and raw satellite remote sensing data using random forest and SVM classifiers.</p>
       <a href="https://github.com/pankajkarman/land-use-land-cover-classification" class="btn btn-primary">Go to Project</a>
    </div>
  </div>
  
    <div class="card">
    <img class="card-img-top" src="/images/tcdf.png" alt="Card image cap" width="300" height="400">
    <div class="card-body">
      <h5 class="card-title" align="left"> <strong> Deep Learning Experiments </strong></h5>
      <p class="card-text" align='justify'>A collection of python scripts to learn and implement various neural network based algorithms like clustering using self organising map, music generation using LSTM, variational autoencoder (VAE) from scratch.</p>
       <a href="https://github.com/pankajkarman/deep-learning" class="btn btn-primary">Go to Project</a>
    </div>
  </div>
  
</div>
  
<br/> 

<div class="card-deck">

  <div class="card">
    <img class="card-img-top" src="/images/droplet.gif" alt="Card image cap" width="300" height="250">
    <div class="card-body">
      <h5 class="card-title"> <strong> Freezing of supercooled water droplet </strong> </h5>
      <p class="card-text" align='justify'>MATLAB and python codes for 
      <a href="https://www.youtube.com/watch?v=6f4lDtwME34">numerical investigation of freezing of sessile water droplet and subsequent transformation of its shape</a>. It simulated the evolution of the interaction between all three phases of water droplet after being placed on a supercooled plate.</p>
      <a href="https://github.com/pankajkarman/droplet" class="btn btn-primary">Go to Project</a>
    </div> 
  </div>

  
  <div class="card">
    <img class="card-img-top" src="/images/pandoc.png" alt="Card image cap" width="300" height="250">
    <div class="card-body">
      <h5 class="card-title"> <strong> markdown-scholar </strong> </h5>
      <p class="card-text" align='justify'>A python tool to convert tables from pandas to latex or markdown format. It has functionality to allow inserting an external table in a markdown document.</p>
      <a href="https://github.com/pankajkarman/markdown-scholar" class="btn btn-primary">Go to Project</a>
    </div> 
  </div>
</div>
  
<br/>

<h1 style="background-color: #ADD8E6; color:#A52A2A">Private libraries</h1>

- [Autoencoder based clustering using self organising maps (AuSOM)](https://github.com/pankajkarman/AuSOM): It is a python library to perform SOM based clustering of trajectories using sequence-to-sequence autoencoder. It is still under development. 

- [Arctic Ozone hole Analysis](https://github.com/pankajkarman/arctic_ozone_hole_2020): A collection of python scripts to analyze ozone hole in Arctic region using various satellite and ground-based measurements and Atmospheric chemistry model. A paper based on this project is in preparation. 

	Analysed satellites include:

	- ACE-FTS
	- MLS
	- OMPS
	- GOME
	- OMI
	
- [Antarctic Ozone hole Analysis](hhttps://github.com/pankajkarman/antarctic_ozone_hole_2019): A collection of python scripts to analyze ozone hole in Antarctic region using various satellite and ground-based measurements and Atmospheric chemistry model. A paper based on this project is in preparation. 

- [Analysis of airmass transport to Antarctica](https://github.com/pankajkarman/AntAir): This repository contains the draft paper and scripts for investigation of long-term trend in the sources of tropospheric ozone in Antarctica. It relies on HyTraj for trajectory generation, receptor modeling and clustering. A paper based on this project is in preparation. Codes will be made public after publication of the paper.

- [Analysis of Antarctic Tropopheric Ozone](https://github.com/pankajkarman/AntTropOz): It contains the draft paper and analysis scripts of the paper **Climate impact of tropospheric ozone trends in Antarctica** which is under review at [ES&T](https://pubs.acs.org/journal/esthag). I intend to make it public once the paper is accepted for publication.

	The scripts include analysis codes for:

	1. Ozonesonde profile and surface ozone data preprocessing.
	2. Calulation of [Tropopause height](https://journals.ametsoc.org/doi/pdf/10.1175/1520-0442%282001%29014%3C3117%3ATTITPR%3E2.0.CO%3B2) from sonde profiles.
	3. [Hellinger distance calculations among profiles](https://www.atmos-chem-phys.net/12/7475/2012/acp-12-7475-2012.html).
	4. [Weighted mean profile calculation](https://www.mdpi.com/1999-4923/9/2/14) for unbalanced sonde dataset and [chi-square correction](https://www.sciencedirect.com/science/article/pii/S1674987117300981).
	5. [SOM clustering of ozone profiles](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1002/2015JD023641). 
	6. [Simple and Multivariate Linear Regression (MLR) trend calculations](www.nature.com/articles/s41598-017-00722-7).
	7. [Bayesian Dynamic linear model (DLM)](https://www.atmos-chem-phys.net/14/9707/2014/acp-14-9707-2014.html) based ozone trend calculation.
	8. [Airmass trajectory generation](https://ieeexplore.ieee.org/document/8452052/) and [clustering using wavelet features](https://ieeexplore.ieee.org/document/7025203).
	9. [Stratosphere-Troposphere Transport calculation](https://www.nature.com/articles/ncomms8105).
	10. [Causal Network Analysis](https://www.nature.com/articles/s41467-019-10105-3) of tropospheric ozone.
	11. [Radiative forcing calculaton using RRTMG](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2008JD009944).

	<p> </p>	
		
- [CausalDiscovery](https://github.com/pankajkarman/CausalDiscovery): A python library for performing causal network analysis. It is still under development. Please have a look at this [paper](https://www.mdpi.com/2504-4990/1/1/19) for an idea about the aim of this library.
