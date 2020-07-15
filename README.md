# MonoCamCalib4AD
This repository mirrors the NAME/URL paper, that summarizes the main camera models used for perspective cameras (narrow and wide-angle), and fisheye cameras, describing the various distortion parameters involved. It provides results on the calibration of a wide-angle camera setup and a fisheye lens setup, comparing the use of various distortion models. Furthermore, it describes the use of homography for perspective transformations between a camera view and a virtual camera view. The main goal of this paper is to provide, in a single document, an overview on monocular camera calibration and bids-eye view perspective transformation, serving as a starting point for researchers starting to work with monocular vision.
Here, it is available all the algorithms used throughout the document, through a Jupyter notebooks using OpenCV 4.1.1, so one can easily experiment and run then without any further installations. \\
**To start, you must open the [Calibration&BirdsEyeView](https://github.com/ipleiria-robotics/MonoCamCalib4AD/blob/master/Calibration&BirdsEyeView.ipynb) file and and go to 
![Alt text](https://colab.research.google.com/assets/colab-badge.svg) shown on top.**

## Calibration algorithm
The calibration algorithms approach the following models:
 * Standard Model
 * Rational Model
 * Thin Prism Model
 * Tilted Model
 * Fisheye Model

Text..

### Wide-angle Lens Example
Distorted             |  Undistorted
:-------------------------:|:-------------------------:
<img width="320" height="240" src="https://github.com/PedroMartins95/Calibration-BirdsEyeView4FisheyeLens/blob/master/1.7mm_original.png">|<img width="320" height="240" src="https://github.com/PedroMartins95/Calibration-BirdsEyeView4FisheyeLens/blob/master/1.7mm_undistorted.png">

### Fisheye Lens Example
Distorted             |  Undistorted
:-------------------------:|:-------------------------:
<img width="320" height="240" src="https://github.com/PedroMartins95/Calibration-BirdsEyeView4FisheyeLens/blob/master/distorted_img.png">|<img width="320" height="240" src="https://github.com/PedroMartins95/Calibration-BirdsEyeView4FisheyeLens/blob/master/undistorted_img.png">

## Homography Results
Text....

### Birds-eye View Example
Distorted             |  Undistorted
:-------------------------:|:-------------------------:
<img width="320" height="240" src="https://github.com/PedroMartins95/Calibration-BirdsEyeView4FisheyeLens/blob/master/undistorted.png">|<img width="320" height="240" src="https://github.com/PedroMartins95/Calibration-BirdsEyeView4FisheyeLens/blob/master/chessboard.png">
