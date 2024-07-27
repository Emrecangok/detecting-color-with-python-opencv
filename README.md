# detecting-color-with-python-opencv
### This project demonstrate how to detecting specific color with python-opencv
### Dont forget to checkrequirements

# How it Works
## Capture Video:
* The script captures video frames from the webcam using OpenCV.

## Convert to HSV:
* Each frame is converted from BGR color space to HSV color space.

## Color Thresholding:
* The get_limits function calculates the lower and upper bounds for the specified color in HSV space. The cv2.inRange function creates a binary mask where the specified color is white and all other colors are black.

## Draw Bounding Box:
* If any object of the specified color is detected, a bounding box is drawn around it in the original frame.

## Display:
* The processed frame is displayed in a window.
