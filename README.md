# CVScan

## Overview
This is the program to extract the main document object from an image. It detects edges, uses the edges to find the outline, and applies perspective transform to obtain the top-down view of the document.

## Dependencies
Install the following dependencies using ``pip``:
* OpenCV
* Numpy
* Scikit-Image
* Imutils

## Usage
``python scan.py --image <filename.jpg>``