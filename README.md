# RITMO Pupillometry Workshop
This repository contains code and toy data for use during Lauren Fink's *Analyzing Pupil Time Series* workshop held during a larger Pupillometry Workshop, April 4-5th, 2022, at the University of Oslo, Centre for Interdisciplinary Studies in Rhythm, Time, and Motion (RITMO).

## Contents
`Fink_RITMO_pupillometry_workshop_interactive.mlx` is the main script we will work with. It contains text, MATLAB code, and interactive user interfaces for understanding some fundamentals of time series analyses. 

`Fink_toydata_RITMO.mat` contains the raw data we will be working with during the workshop. 

The other two scripts are help functions, called in the main interactive script: 

`genPRF.m` is a function to generate a pupillary response function, called in the interactive script.  

`getFFT.m` is a function to calculate the Fast Fourier Transform of an input signal. 

## Dependencies
This code was written in MATLAB version 2021b and relies on the following:
- Signal Processing Toolbox
- Statistics Toolbox
- Symbolic Toolbox

## Citation
If using anything from this repository, cite:

Fink, L., Simola, J., Tavano, A., Lange, E. B., Wallot, S., & Laeng, B. (2021, December 2). From pre-processing to advanced dynamic modeling of pupil data. https://doi.org/10.31234/osf.io/wqvue

AND/OR 

Fink, L. K., Hurley, B. K., Geng, J. J., & Janata, P. (2018). A linear oscillator model predicts dynamic temporal attention and pupillary entrainment to rhythmic patterns. Journal of Eye Movement Research, 11(2). https://doi.org/10.16910/jemr.11.2.12 
