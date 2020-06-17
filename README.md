# Scikit-downscale: an open source Python package for scalable climate downscaling

[![Binder](https://binder.pangeo.io/badge_logo.svg)](https://binder.pangeo.io/v2/gh/earthcube2020/ec20_hamman_etal/master)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)


Joseph Hamman (jhamman@ucar.edu) and Julia Kent (jkent@ucar.edu)

NCAR, Boulder, CO, USA

Climate data from Earth System Models are increasingly being used to study the impacts of climate change on a broad range of biogeophysical (forest fires, fisheries, etc.) and human systems (reservoir operations, urban heat waves, etc.). Before this data can be used to study many of these systems, post-processing steps commonly referred to as bias correction and statistical downscaling must be performed. “Bias correction” is used to correct persistent biases in climate model output and “statistical downscaling” is used to increase the spatiotemporal resolution of the model output (i.e. 1 deg to 1/16th deg grid boxes). For our purposes, we’ll refer to both parts as “downscaling”.

In the past few decades, the applications community has developed a plethora of downscaling methods. Many of these methods are ad-hoc collections of post processing routines while others target very specific applications. The proliferation of downscaling methods has left the climate applications community with an overwhelming body of research to sort through without much in the form of synthesis guilding method selection or applicability.

Motivated by the pressing socio-environmental challenges of climate change – and with the learnings from previous downscaling efforts in mind – we have begun working on a community-centered open framework for climate downscaling: scikit-downscale. We believe that the community will benefit from the presence of a well-designed open source downscaling toolbox with standard interfaces alongside a repository of benchmark data to test and evaluate new and existing downscaling methods.

In this notebook, we provide an overview of the scikit-downscale project, detailing how it can be used to downscale a range of surface climate variables such as air temperature and precipitation. We also highlight how scikit-downscale framework is being used to compare exisiting methods and how it can be extended to support the development of new downscaling methods.

-------

This notebook was developed for the [2020 EarthCube All Hands Meeting](https://www.earthcube.org/EC2020). The development of [Scikit-downscale](https://scikit-downscale.readthedocs.io/en/latest/) done in conjunction with the development of the [Pangeo Project](http://pangeo.io/) and was supported by the following awards:

- [NSF-GEO-AGS 1928374: EarthCube Data Capabilities: Collaborative Proposal: Jupyter meets the Earth: Enabling discovery in geoscience through interactive computing at scale](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1740633)
- [NSF-OIA 1937136: Convergence Accelerator Phase I (RAISE): Knowledge Open Network Queries for Research (KONQUER)](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1937136)

ECAHM 2020 ID: 143

-------

## License Information

The notebook in this repository is licensed under [CC-BY](https://creativecommons.org/licenses/by/4.0/). Scikit-downscale is licensed under [Apache License 2.0](https://github.com/jhamman/scikit-downscale/blob/master/LICENSE).
