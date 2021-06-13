# Object distance
Vision Project - part 2

## Libraries and Sources
To proceed, you need to have the VLFeat library installed on your computer. You can use both Linux and Anaconda.

[VLFeat](http://www.vlfeat.org/)

This activity is based on chapter 4 of the book [Programming Computer Vision with Python](http://programmingcomputervision.com/)

You can generate the camera calibration using [GML Camera Calibration Toolbox](http://graphics.cs.msu.ru/en/node/909)

How to obtain Euler angles from rotatiin matrix [How to obtain Euler angles from rotation matrix] (http://www.staff.city.ac.uk/~sbbh653/publications/euler.pdf)

## Configurations:
Study cv_adapted.py and cv_adapted_webcam.py, which are based on ch4_ar_cube.py; see the corresponding chapter on Programming Computer Vision with Python.

Generate a calibration file from your camera (probably your laptop's webcam). Section 4.2 of the book explains how to do it.

See how to do it in the book. You can also configure your smartphone's camera as a webcam (there are apps for that)
Adapt ch4_ar_cube.py to use images from your webcam. When done, use cv_adapted_webcam.py

# Project
This project constantly prints its distance in relation to a marker (x, y, and z coordinates) of the camera.

Define a point in space as your goal

Instructions on how to move to get to the target point are printed.

When the camera is less than 0.5 m from the target, it is printed: "you are here!"
