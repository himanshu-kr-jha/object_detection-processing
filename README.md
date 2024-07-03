
# Object Detection and video processing

This project is about detection of the boom of heavy duty vehicles and track its movement and give its state.


## About the project

- The project used custom trained YOLOv5 model to detect the boom of the vehicle.
- It tracks the movement of the boom accounting the centroid of the bounding box of the detected part.
- It also accounts for the background subtraction of region of interest of the frame to get information about the motion detection of the boom.
- COllectively using both of the features it give the state of the boom i.e working, moving, idle.


## Authors

[@himanshu-kr-jha](https://www.github.com/himanshu-kr-jha)

