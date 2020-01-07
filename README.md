# raster_geostatistics
[![DOI](https://zenodo.org/badge/150665172.svg)](https://zenodo.org/badge/latestdoi/150665172)


This repository contains notebooks for semivariogram analysis involving point or raster data. 
- Uses [GSLIB](http://www.gslib.com/) under the hood
- Python wrapper function around GSLIB were originally developed by [Micheal Pyrcz](http://www.michaelpyrcz.com/) , 
[GeostatsPy](https://github.com/GeostatsGuy/GeostatsPy) . I just made some minor modifications to it. Credits for the package directly go to the authors (Micheal and team).

Notebooks which were used in analysing High Mountain Asia Glacier Mass balance paper include:
- [Mass_balance_cor_working.ipynb](https://github.com/ShashankBice/raster_geostatistics/blob/master/Mass_balance_cor_working.ipynb) : Semivariogram analysis for glacier mass balance errors
- [dh_dt_sigma_error.ipynb](https://github.com/ShashankBice/raster_geostatistics/blob/master/dh_dt_sigma_error.ipynb) : Semivariogram analysis for elevation change rate (dh/dt) error at glacier scale. 
- [nogzumpa_dh_dt_error_correlation.ipynb](https://github.com/ShashankBice/raster_geostatistics/blob/master/nogzumpa_dh_dt_error_correlation.ipynb) : Semivariogram analysis for elevation change rate (dh/dt) error at pixel scale, over a sample area around Nogzumpa Glacier.

These notebooks were primarily used to assess the length scales till which errors were correlated for glacier mass balance, elevation change and for errors in dh/dt maps over static surfaces.
