# Gammapy - an open source package for high energy astrophysics

Gammapy, an open source python package selected as the CTA Science tools, is a community-developed, open source Python package built on Numpy, Scipy and Astropy using open FITS based data formats. It is used for the analysis of gamma-ray data of many instruments including Imaging Atmospheric Cherenkov Telescopes (IACT; eg: CTA, H.E.S.S. and MAGIC), Water Cherenkov Detectors (WCD; eg: HAWC), as well as space based observatories (eg: Fermi-LAT). 

Starting from event list and instrument response functions at the so called "Data Level 3", gammapy provides pipelines for reduction of the input data to binned WCS, HEALPix or region based data structures. A variety of background reduction methods, including traditional techniques like the Reflected and Ring regions, as well as novel 3D Field of View Likelihood techniques, are supported. Counts, background and IRFs data are bundled in datasets ("Data Level 3") and can be serialised, rebinned and stacked. 

Modelling of datasets are supported using Poisson maximum likelihood fitting. While a variety of in-built spectral, temporal and spatial models are supplied, it also supports custom user defined models, eg: energy dependent morphology for galactic accelerators or temporal models with spectroscopic variability for blazars. Moreover, it enables joint likelihood analysis between different datasets, thus providing a simple platform for handling time dependent instrument response, different classes of events, or performing a combined multi-instrument analysis. Gammapy also implements methods to estimate flux points, including likelihood profiles per energy bin, light curves as well as flux and signficance maps in energy bins

A long-term stable release of Gammapy, v1.0, is scheduled for this summer. This contribution will present and overview of the package, describing the development history and demonstrate some key analysis features using H.E.S.S, Fermi-LAT and simulated CTA data.


