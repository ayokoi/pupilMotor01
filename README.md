# Pupil diameter tracked during motor adaptation in humans: MATLAB codes and related data (coming soon)

This repository contains MATLAB codes and related data to reproduce the Figures (except for schematics) and related analyses in Yokoi and Weiler (2022) paper "Pupil diameter tracked during motor adaptation in humans" (doi: https://doi.org/10.1152/jn.00021.2022). Each sub-folders contains codes (`/code`), data (`/data`), and some resultant figures (`/figure`), respectively. To make the codes work, all the contents (i.e., `/code`, `/data`, and `/figure`) of this repository need to be downloaded.

## Dependency
The following softwares/toolboxes need to be correctly installed to run the present code.
- MATLAB R2015b (consistency is not guaranteed for other versions)
- Statistics and Machine Learning Toolbox (for fitlme.m)
- Image Processing Toolbox (for bwconncomp.m in permutest.m)
- Dataframe Toolbox (https://github.com/jdiedrichsen/dataframe)

Note also that I haven't tested if the code correctly works on PCs.

## Main functions to reproduce figures
Here is a short summary of the main code for reproducing the figures. For more detail, see help messages for the function. 
 
|Function |Description |Example |
|----|--------|----|
|xxxx.m |Reproduces figures for behavioral analyses. | `xxxx('Figure_all')` |
