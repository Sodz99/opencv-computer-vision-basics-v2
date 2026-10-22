# OpenCv Computer Visison

The project aims to understand OpenCV and build some applications of how to use the OpenCV library.

## Overview
OpenCV (Open-Source Computer Vision Library: http://opencv.org) is an open-source library that includes several hundreds of computer vision algorithms. OpenCV has a modular structure, which means that the package includes several shared or static libraries.

OpenCV is a huge open-source library for computer vision, machine learning, and image processing. It can process images and videos to identify objects, faces, or even the handwriting of a human. When integrated with various libraries, such as “NumPy,” a highly optimized library for numerical operations, the number of weapons increases in your Arsenal, i.e., whatever operations one can do in NumPy can be combined with OpenCV.

## Data
In this project, we will use three sample images (jpg) and a video (mp4) as our input data and perform various operations on top of it.

_Data is not included in this repository._

## Approach
1. Importing the required libraries.
2. Perform reading, writing, and displaying an image.
3. Perform arithmetic operations like addition and subtraction on images
4. Create a function for color spacing and conversion
5. Create a function for Image thresholding
6. Create a function for Image smoothing
7. Create a function for Morphological Transformation
8. Perform edge detection of an image with Canny Edge Detection
9. Perform template matching and multi-scale template matching
10. Create a function for Hough Transformation
11. Perform video processing
12. Perform Harris Corner detection
13. Perform feature Detection and Extraction using SIFT
14. Create a function for feature matching with Flann and Brute force
15. Perform face and eye detection

Modular code overview

Once you unzip the modular_code.zip file you can find the following folders within it.
1. Input
2. Source Folder
3. Output
1. Input folder - It contains all the data that we have for analysis. Here we have three sample images and one video image for performing different operations using OpenCV.
2. Source folder - This is the most important folder of the project. This folder contains all the modularized code for all the above steps in a modularized manner. This folder consists of:  Engine.py  ML_Pipeline The ML_pipeline is a folder that contains all the functions put into different python files which are appropriately named. These python functions are then called inside the engine.py file.
3. Output folder – The output folder contains output images generated after running all the functions created. There are approximately 25 output images and one data folder which has frames after video processing.

## Tech stack
 Language - Python  Libraries - numpy, matplotlib, cv2(OpenCV)

## How to run
```bash
pip install -r modular_code/Source_Folder/requirements.txt
```

## Project structure
```
.gitignore
README.md
modular_code/
  Output/
    __init__.py
  Source_Folder/
    Engine.py
    ML_Pipeline/
    Readme.md
    __init__.py
    requirements.txt
```

## Credits
Based on a ProjectPro guided project.
