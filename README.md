# CarND Term1 Starter Kit

[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)
## Lane Line Dectection
### system
`Linux`
### environment 
[Anaconda Environment](doc/configure_via_anaconda.md) from udacity
### way
 1. transfrom the img from RGB to HSV.
 2. recognise the yellow color and white color in HSV image.(yellow and white are different)
 3. transform to GRAY
 4. gaussian blur
 5. detect edges using canny
 6. get ROI, and then apply to edges.
 7. hough transform to detect lines.
 8. draw lines in the image. Please remember that the `edges in the road are continuously！`
### purpose
The purpose of this project is to provide unified software dependency support for students enrolled in Term 1 of the [Udacity Self-Driving Car Engineer Nanodegree](https://www.udacity.com/course/self-driving-car-engineer-nanodegree--nd013).


