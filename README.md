# Udacity Self-Driving-Car-Projects

# Project 1 - Detect Lane Lines
The lane detection project uses various image processing techniques to isolate the area of interest and 
detect the lane lines painted on the road.  The project introduced the concept of an image pipeline where
images are passed through and the lane line positions are extracted.  The pipeline consists of the following
stages:

* grayscale
* guassian blur
* canny transform
* region of interest processing
* hough transform

The hough transform output is processed to detect the slope of the lines.  The resulting lines are drawn
on the image.

![Yellow](proj1/yellow.gif "Video with Yellow Lines")
![White](proj1/white.gif "Video with White Lines")
![Extra](proj1/extra.gif  "Challenge Video")

# Project 3 - Self-Driving Car using CNN

![Race Track](proj3/racetrack.gif)
![Off Road](proj3/offroad.gif)

# Project 4 - Advanced Lane Detection

In the advanced lane detection project, a different approach was taken.

![Project](proj4/project.gif)
