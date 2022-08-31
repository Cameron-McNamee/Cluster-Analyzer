# Cluster-Analyzer
This project is run in MATLAB
The goal of this project is to take in an image of cells and return a density given by that image. 
This project uses some of the available tools in MATLAB's image processing toolbox. 
This program operates best on input images with a proper pixel density. For the project I designed, 
this was 750x750 pixels. To determine optimal pixel density, modify the dimensions of your raw image 
and observe what dimensions provide the more accurate amount of signal. Too dense of an image will
yeild an output with a lot of noise. Not dense enough will cause high levels of signal loss. 

Cell density is determined by the half radius, or the radius about the geometric center that contains
half the population of total cells. In order to determine the clustering rate, one must input images
over time and use the densities given to then calculate this value. It is important to note that 
in this file the constant of 0.8333 is used to convert from pixels to micrometers. This constant 
was derived by my specific project and you should adapt this value to your images. 

For questions, email me at cmcnamee@caltech.edu
