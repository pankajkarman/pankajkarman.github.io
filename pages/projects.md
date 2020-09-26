<!--
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

- [markdown-scholar](https://github.com/pankajkarman/markdown-scholar): A python tool to convert tables from pandas to latex or markdown format.

- [Remote Sensing](https://github.com/pankajkarman/satelite): A collection of python scripts to read and correct atmospheric composition profile data from various satellites ([GOME2](https://www.esa.int/Applications/Observing_the_Earth/Meteorological_missions/MetOp/About_GOME-2), [Aura-MLS](https://mls.jpl.nasa.gov/) and [OMPS](https://www.ball.com/aerospace/programs/omps)) like geopotential height, Temperature, ozone, water vapor, N<sub>2</sub>O, ClO and HNO<sub>3</sub>.

- [bias-correction](https://github.com/pankajkarman/bias_correction): A python library to perform bias correction of datasets in order to remove cross-dataset biases. Implemented methods include quantile mapping, modified quantile mapping, scaled distribution mapping (both Gamma and Normal corrections).

- [pyvortex](https://github.com/pankajkarman/pyvortex): A python module to calculate [equivalent latitude](https://en.wikipedia.org/wiki/Equivalent_latitude) and edge of a polar vortex using [Nash criteria](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/96JD00066).

- [Freezing of supercooled water droplet](https://github.com/pankajkarman/droplet): MATLAB and python codes for [numerical investigation of freezing of sessile water droplet and subsequent transformation of its shape](https://www.youtube.com/watch?v=6f4lDtwME34). It simulated the evolution of the interaction between all three phases of water droplet after being placed on a supercooled plate.

- [Artifical Intelligence Projects](https://github.com/pankajkarman/Artifical-Intelligence-Projects): A collection of projects implementing various machine learning methods in python. It also contains a project implementing a Question answering model using Dynamic memory network (DMN) based on Stanford Question Answering Dataset (SQuAD) dataset.

- [Deep Learning Experiments](https://github.com/pankajkarman/deep-learning): A collection of python scripts to learn and implement various neural network based algorithms from scratch.

- [Arctic Ozone hole Analysis](https://github.com/pankajkarman/arctic_ozone_hole_2020): A collection of python scripts to analyze ozone hole in Arctic region using various satellite and ground-based measurements and Atmospheric chemistry model. A paper based on this project is in preparation. 

	Analysed satellites include:

	- ACE-FTS
	- MLS
	- OMPS
	- GOME
	- OMI
	
- [Antarctic Ozone hole Analysis](hhttps://github.com/pankajkarman/antarctic_ozone_hole_2019): A collection of python scripts to analyze ozone hole in Antarctic region using various satellite and ground-based measurements and Atmospheric chemistry model. A paper based on this project is in preparation. 

- [HyTraj](https://github.com/pankajkarman/HyTraj): It is a python library, still under development, for performing receptor modeling using trajectories generated with HYSPLIT model. It'll have functions for generating large number of air-parcel trajectories with parallel processing; reducing the trajectories generation time. It will also have appropriate tools for clustering trajectories using different clustering techniques.

- [Analysis of airmass transport to Antarctica](https://github.com/pankajkarman/AntAir): This repository contains the draft paper and scripts for investigation of long-term trend in the sources of tropospheric ozone in Antarctica. It relies on HyTraj for trajectory generation, receptor modeling and clustering. A paper based on this project is in preparation. Codes will be made public after publication of the paper.

- [Analysis of Antarctic Tropopheric Ozone](https://github.com/pankajkarman/AntTropOz): It contains the draft paper and analysis scripts of the paper **Climate impact of tropospheric ozone trends in Antarctica** which is under review at [ES&T](https://pubs.acs.org/journal/esthag). I intend to make it public once the paper is accepted for publication.

	The scripts include analysis codes for:

	1. Ozonesonde profile and surface ozone data preprocessing.
	2. Calulation of [Tropopause height](https://journals.ametsoc.org/doi/pdf/10.1175/1520-0442%282001%29014%3C3117%3ATTITPR%3E2.0.CO%3B2) from sonde profiles.
	2. [Hellinger distance calculations among profiles](https://www.atmos-chem-phys.net/12/7475/2012/acp-12-7475-2012.html).
	3. [Weighted mean profile calculation](https://www.mdpi.com/1999-4923/9/2/14) for unbalanced sonde dataset and [chi-square correction](https://www.sciencedirect.com/science/article/pii/S1674987117300981).
	4. [SOM clustering of ozone profiles](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1002/2015JD023641). 
	5. [Simple and Multivariate Linear Regression (MLR) trend calculations](www.nature.com/articles/s41598-017-00722-7).
	5. [Bayesian Dynamic linear model (DLM)](https://www.atmos-chem-phys.net/14/9707/2014/acp-14-9707-2014.html) based ozone trend calculation.
	6. [Airmass trajectory generation](https://ieeexplore.ieee.org/document/8452052/) and [clustering using wavelet features](https://ieeexplore.ieee.org/document/7025203).
	7. [Stratosphere-Troposphere Transport calculation](https://www.nature.com/articles/ncomms8105).
	7. [Causal Network Analysis](https://www.nature.com/articles/s41467-019-10105-3) of tropospheric ozone.
	8. [Radiative forcing calculaton using RRTMG](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2008JD009944).
	
- [Land Use Land Cover (LULC) classification](https://github.com/pankajkarman/land-use-land-cover-classification): A collection of python scripts to perform LULC analysis using satellite remote sensing data using random forest and SVM classifiers. Since a journal paper is in preparation based on the methods implemented in this repository, repository will be made public after the puplication of paper. These scripts include functions for data preprocessing:
	1. False color composite (FCC) creation.
	1. Digital Number (DN) conversion to Top of Atmosphere (TOA) Reflectance.
	1. Atmospheric correction using Dark Object Subtraction (DOS).
	1. Cloud correction using time series data.
	1. Color balancing using Contrast Local Adaptive Histogram Equalisation (CLAHE) and contrast stretching.
	1. Reprojection to WGS84 coordinates.
	1. Mosaicing and clipping of rasters using shapefile.
	1. Rasterize training shapefiles necessary for classification.	
	
     It also implements the same using Google Earth Engine platform in python.

- [Autoencoder based clustering using self organising maps (AuSOM)](https://github.com/pankajkarman/AuSOM): It is a python library to perform SOM based clustering of trajectories using sequence-to-sequence autoencoder. It is still under development. 

- [CausalDiscovery](https://github.com/pankajkarman/CausalDiscovery): A python library for performing causal network analysis using Transformer based architecture. It is still under development. Please have a look at this [paper](https://www.mdpi.com/2504-4990/1/1/19) for an idea about the aim of this library.
