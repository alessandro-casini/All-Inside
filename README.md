<head>
     <link rel="shortcut icon" type="image/x-icon" href="favicon.ico">
  </head>

## Introduction

Change-point methods are useful for detecting parameter instabilities or changes in the moments of the data. The package provides tools for simultaneously detecting abrupt (i.e., breaks) or smooth change-points in any of the following features of a time series: mean, variance, covariance and autocorrelation. 

Many change-point methods along with corresponding codes have been developed in the literature. Each method/code focuses on a specific feature of a time series and a specific type of break. All-Inside includes a single change-point procedure that is useful for any feature and any type of break. The user needs to just run a single code. That is why it is named <p>All-Inside</p>.   

The methods are based on frequency domain statistics as developed in [Casini and Perron (2021)](https://alessandro-casini.com/wp-content/uploads/2021/03/CASINI_PERRON_Change-Point_Spectrum_SLS.pdf), "Change-Point Analysis of Time Series with Evolutionary Spectra". The methods are also useful for the choice of subsamples for regression analyses.

## Non-Technical Summary for Empirical Research
[Download Non-Technical Summary here.](https://github.com/alessandro-casini/All-Inside/blob/main/CASINI_PERRON_All-Inside_Non-Technical.pdf)

## Software available in Matlab, R and Stata

* [Matlab Package](https://github.com/alessandro-casini/Change-Point_All-Inside.github.io/blob/main/All-Inside_Matlab.rar)
* R Package (to be uploaded later)
* Stata Package (to be uploaded later)

## Contributors
* [Federico Belotti](https://economia.uniroma2.it/faculty/333/belotti-federico), University of Rome Tor Vergata.
* [Alessandro Casini](https://alessandro-casini.com), University of Rome Tor Vergata.
* [Leopoldo Catania](https://pure.au.dk/portal/en/persons/id(5d29f2ff-3942-4a3d-a74d-006b55ae3836).html), Aarhus University.
* [Stefano Grassi](https://economia.uniroma2.it/faculty/412/grassi-stefano), University of Rome Tor Vergata.
* [Pierre Perron](http://blogs.bu.edu/perron/), Boston University.

## Background Papers
* Belotti, F., A. Casini, L. Catania, S. Grassi and P. Perron, "Simultaneous Bandwidths Determination for DK-HAC Estimators and Long-Run Variance Estimation in Nonparametric Settings". arXiv preprint arXiv 
* Casini, A. (2019), ["Improved Methods for Statistical Inference in the Context of Various Types of Parameter Variation"](https://open.bu.edu/handle/2144/38750). Ph.D Dissertation, Boston University.
* Casini, A. (2021), ["Theory of Evolutionary Spectra for Heteroskedasticity and Autocorrelation Robust Inference in Possibly Misspecified and Nonstationary Models"](https://alessandro-casini.com/research/). arXiv preprint arXiv.
* Casini, A. and P. Perron (2021), "Change-Point Analysis of Time Series with Evolutionary Spectra". arXiv preprint arXiv 

## Maintainer and Correspondence
* [Alessandro Casini](https://alessandro-casini.com), University of Rome Tor Vergata.
