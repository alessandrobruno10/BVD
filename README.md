# BVD
Blood Vessel Detection is a MATLAB code repository. The code is applied over immunohistochemistry images for detecting Blood Vessels.

The package is a zip file and the scripts and functions have been tested on MATLAB_R2019a.

Once you download and uncompress the zip file you will find a new directory named BVD. In this folder you will find four files that are necessary to run the algorithm for the bloodvessel detection: 

batch.m  # this is a script that is employed to run bv_detection in a batch mode
bv_detection.m #this is the main file to run by using the following syntax: 
OUT = bv_detection(filename) 
filename is the image name whose bloodvessels you are interested in.

drawArrow.m #this file contains an ancillary function that simply draw out rows to highlith the locations of the detected blood vessels

holes_detector.m #as easily understandable from the file name, this function allows for the detection of holes in a given image

lumen_percentage.m #this function compute the percentage of lumen for a given input image

Remarks on the algorithm: it can be run only with RGB images
