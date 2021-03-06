Profile Classification Modelling (PCM)
======================================
[![DOI](https://img.shields.io/badge/DOI--Article-10.1016%2Fj.pocean.2016.12.008-orange.svg)](http://dx.doi.org/10.1016/j.pocean.2016.12.008)  

[![license](https://img.shields.io/github/license/mashape/apistatus.svg)]()

**Profile Classification Modelling** is a scientific analysis approach based on vertical profiles classification that can be used in a variety of oceanographic problems (front detection, water mass identification, natural region contouring, reference profile selection for validation, etc ...).  
It is being developed at Ifremer/LOPS in collaboration with IMT Atlantique since 2015, and has become mature enough (with publication and communications) to be distributed and made publicly available for continuous improvements with a community development.

**Ocean dynamics** and its 3-dimensional structure and variability is so complex that it is very difficult to develop objective and efficient diagnostics of horizontally and vertically coherent oceanic patterns. However, identifying such **patterns** is crucial to the understanding of interior mechanisms as, for instance, the integrand giving rise to Global Ocean Indicators (e.g. heat content and sea level rise). We believe that, by using state of the art **machine learning** algorithms and by building on the increasing availability of ever-larger **in situ and numerical model datasets**, we can address this challenge in a way that was simply not possible a few years ago. Following this approach, **Profile Classification Modelling** focuses on the smart identification of vertically coherent patterns and their spatial distribution.

*References*: 

- Maze, G., et al. Coherent heat patterns revealed by unsupervised classification of Argo temperature profiles in the North Atlantic Ocean. *Progress in Oceanography*, 151, 275-292 (2017)  
    [http://dx.doi.org/10.1016/j.pocean.2016.12.008](http://dx.doi.org/10.1016/j.pocean.2016.12.008)
- Maze, G., et al. Profile Classification Models. *Mercator Ocean Journal*, 55, 48-56 (2017).   
    [http://archimer.ifremer.fr/doc/00387/49816](http://archimer.ifremer.fr/doc/00387/49816)
- Maze, G. A Profile Classification Model from North-Atlantic Argo temperature data. *SEANOE Sea scientific open data edition*.  
    [http://doi.org/10.17882/47106](http://doi.org/10.17882/47106)

## Python package
[![Python 2.7](https://img.shields.io/badge/python-2.7-blue.svg)](https://www.python.org/downloads/release/python-270/) [![](https://img.shields.io/badge/xarray-0.10.0-blue.svg)](http://xarray.pydata.org/en/stable/) 

We are currently developing a Python package to work with PCM easily.  
**You can check out the first release on the [pyXpcm](https://github.com/obidam/pyxpcm) homepage.**  
Otherwise you can still [look at a
classic PCM workflow on this notebook](https://github.com/obidam/pcm/blob/master/python/PCM-workflow-classic-demo.ipynb).

## Matlab toolbox
[![DOI](https://img.shields.io/badge/DOI--Matlab-10.5281%2Fzenodo.400018-orange.svg)](http://dx.doi.org/10.5281/zenodo.400018) [![](https://img.shields.io/badge/matlab->R2016b-blue.svg)]()  

This is the original code for PCM used in [Maze et al (2017)](http://dx.doi.org/10.1016/j.pocean.2016.12.008).  

[You can get started with the Matlab toolobx following this wiki page](https://github.com/obidam/pcm/blob/master/matlab/README.md)

Note that @gmaze will provide help to use it, but won't maintain the code. Contact us if you want to contribute !

