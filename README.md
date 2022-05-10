# RITMO Pupillometry Workshop
This repository contains code and toy data for use during Lauren Fink's *Analyzing Pupil Time Series* workshop held during a larger [Pupillometry Workshop, April 4-5th, 2022, at the University of Oslo, Centre for Interdisciplinary Studies in Rhythm, Time, and Motion (RITMO)](https://www.uio.no/ritmo/english/projects/ritpart/events/workshops/2022/pupillometry/index.html).  

[You can watch the recorded workshop here](https://www.uio.no/ritmo/english/projects/ritpart/events/workshops/2022/pupillometry/videos/11-fink.mp4?vrtx=view-as-webpage), while following along with the code in the repository. 

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

## Running this code
Download this Github repository. Open `Fink_RITMO_pupillometry_workshop_interactive.mlx`. 

As long as all files have stayed in the same folder, MATLAB should find the required data and functions and all should run without problem. 

Should trouble occur, or bugs be found, please [open an issue](https://github.com/lkfink/RITMO_pupil_workshop/issues).

## Citation
If using anything from this repository, cite:

Fink, L., Simola, J., Tavano, A., Lange, E. B., Wallot, S., & Laeng, B. (2021, December 2). From pre-processing to advanced dynamic modeling of pupil data. https://doi.org/10.31234/osf.io/wqvue

AND/OR 

Fink, L. K., Hurley, B. K., Geng, J. J., & Janata, P. (2018). A linear oscillator model predicts dynamic temporal attention and pupillary entrainment to rhythmic patterns. Journal of Eye Movement Research, 11(2). https://doi.org/10.16910/jemr.11.2.12 
