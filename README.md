# Pepper ROS Packages (Robocup@home)

### This is a ROS launch file of packages to apply to the Pepper using open source. 
(It was written at the MMMIL Laboratory at Gachon University.)




## 1. depth2scan.launch
This is a file for converting depthimage data to laser data. This used the depthimage_to_lasercan of the ROS packages.
(http://wiki.ros.org/depthimage_to_laserscan)


## 2. marker_finder_pepper.launch
This is a file for recognition of a marker using Pepper's front camera.  This used the aruco_ros of the ROS packages.
(https://github.com/pal-robotics/aruco_ros)


## 3. object_detection_pepper.launch
This is a file for object detection using Pepper's front camera. This used the ROS package made with the Tensorflow object detection API.\
Use ssd_mobilinet_v1_coco_11_06_2017 as the default model.

(https://github.com/osrf/tensorflow_object_detector)


## 4. object_localization_pepper.launch
