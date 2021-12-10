# Road-Lane-line-detection-Computer-Vision-Project-
IDEA ---> The lines drawn on the roads guide human drivers where the lanes are. It also refers to the direction to steer the vehicle. This application is cardinal for developing driverless cars.

Note regarding the project Road Lane-Line Detection with Python & OpenCV::
1. You can build an application having the ability to identify track lines from input images or continuous video frames.
2. Lane Line detection is a critical component for self driving cars and also for computer vision in general. This concept is used to describe the path for self-driving cars and to avoid the risk of getting in another lane.
3. We will be using the concepts of computer vision using OpenCV library in our project. To detect the lane we have to detect the white markings on both sides on the lane.
4. Using computer vision techniques in Python, we will identify road lane lines in which autonomous cars must run. This will be a critical part of autonomous cars, as the self-driving cars should not cross it’s lane and should not go in opposite lane to avoid accidents.

## Image ::
![Road_lane_line_detection_openCV](https://user-images.githubusercontent.com/55339677/145614421-de3f0431-0577-4322-8975-1e584bfcf1b5.png)


## Frame Masking and Hough line transformation ::
    a.) To detect white markings in the lane, first, we need to mask the rest part of the frame. We do this using frame masking
    b.) The frame is nothing but a NumPy array of image pixel values.To mask the unnecessary pixel of the frame, we simply update those pixel values to 0 in the NumPy array.
    
## After masking we need to detect lane lines::
    a.) The technique used to detect mathematical shapes like this is called Hough Transform.
    b.) Hough transformation can detect shapes like rectangles, circles, triangles, and lines.
   
## Summary::
In this lane line detection project, we use OpenCV. Before detecting lane lines, we masked remaining objects and then identified the line with Hough transformation.
