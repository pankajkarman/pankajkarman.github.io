<!--
.. title: Projects
.. slug: projects
.. date: 2020-05-05 20:11:51 UTC+05:30
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text
-->

- [markdown-scholar](https://github.com/pankajkarman/markdown-scholar): A python tool to convert tables from pandas to latex or markdown format.

- [water-droplet-freezing](https://github.com/pankajkarman/water-droplet-freezing): MATLAB and python codes for [numerical investigation of freezing of sessile water droplet and subsequent transformation of its shape](https://aapt.scitation.org/doi/abs/10.1119/1.4726201?journalCode=ajp). It simulated the evolution of the interaction between all three phase of water droplet after being placed on a supercooled plate. The repository will be made open very soon.

- [Artifical-Intelligence-Projects](https://github.com/pankajkarman/Artifical-Intelligence-Projects): A collection of projects implementing various machine learning methods from scratch in python. It also contains a project implementing a Question answering model using Dynamic memory network (DMN) based on Stanford Question Answering Dataset (SQuAD) dataset.

- HyTraj: It is a python library, still under development, for performing receptor modeling using trajectories generated with HYSPLIT model. It'll have functions for generating large number of air-parcel trajectories with parallel processing; reducing the trajectories generation time. It will also have appropriate tools for clustering trajectories using different clustering techniques.

- [AntAir](https://github.com/pankajkarman/AntAir): This project contains the draft paper and scripts for investigation of long-term trend in the sources of tropospheric ozone in Antarctica. It relies on HyTraj for trajectory generation, receptor modeling and clustering. A paper based on this project is under preparation. Codes will be made public after publication of the paper.

- [AntTropOz](https://github.com/pankajkarman/AntTropOz): It contains the draft paper and analysis scripts of the paper **Climate impact of tropospheric ozone trends in Antarctica** which is under review at ES&T. I intend to make it public once the paper is accepted for publication.

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

- land-use-land-cover-classification: A collection of python scripts to perform LULC analysis using satellite remote sensing data using random forest and SVM classifiers. Since a journal paper is under preparation based on the methods implemented in this repository, repository will be made public after the puplication of paper. These scripts include functions for data preprocessing:
	1. False color composite (FCC) creation.
	1. Digital Number (DN) conversion to Top of Atmosphere (TOA) Reflectance.
	1. Atmospheric correction using Dark Object Subtraction (DOS).
	1. Cloud correction using time series data.
	1. Color balancing using Contrast Local Adaptive Histogram Equalisation (CLAHE) and contrast stretching.
	1. Reprojection to WGS84 coordinates.
	1. Mosaicing and clipping of rasters using shapefile.
	1. Rasterize training shapefiles necessary for classification.
	
	
     It also implements the same using Google Earth Engine platform in python.

- [Autoencoder based clustering using self organising maps (AuSOM)](https://github.com/pankajkarman/AuSOM): It is a python library to perform SOM based clustering of trajectories using sequence-to-sequence autoencoder. It is still under development, and will be open shortly. 

- [CausalDiscovery](https://github.com/pankajkarman/CausalDiscovery): A python library for performing causal network analysis using Transformer based architecture. It is still under development. Please have a look at this [paper](https://www.mdpi.com/2504-4990/1/1/19) for an idea about the aim of this library.
