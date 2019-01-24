# Pepper ROS Packages (Robocup@home)

### This is a ROS launch file of packages to apply to the Pepper using open source. 
(It was written by Steve Jeong at the MMMIL Laboratory at Gachon University.)

### 1. depth2scan.launch
This is a file for converting depthimage data to laser data. This used the depthimage_to_lasercan of the ROS packages.

(http://wiki.ros.org/depthimage_to_laserscan)


### 2. marker_finder_pepper.launch
This is a file for recognition of a marker using Pepper's front camera.  This used the aruco_ros of the ROS packages.

(https://github.com/pal-robotics/aruco_ros)


### 3. object_detection_pepper.launch
This is a file for object detection using Pepper's front camera. This used the ROS package made with the Tensorflow object detection API. Use ssd_mobilinet_v1_coco_11_06_2017 as the default model.

(https://github.com/osrf/tensorflow_object_detector)


### 4. object_localization_pepper.launch
This is a file for object localization using Pepper's front camera and depth camera. This used the ROS package made with the Tensorflow object detection API. (dodo_detector)
You need to take a Tensorflow model and save it in the path to use this file.

(https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/detection_model_zoo.md)
(https://github.com/douglasrizzo/dodo_detector)


### 5. pepper_test_slam.launch
This is a file for SLAM using gmapping. By default, the depth data of the pepper is used to proceed to SLAM. In some cases, the bumper laser sensor can be replaced. This links to file 1.
(http://wiki.ros.org/gmapping)