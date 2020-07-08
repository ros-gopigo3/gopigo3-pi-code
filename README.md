# GoPiGo3 ROS package
Packages to be included in the Raspberry Pi of robot to run the examples in the book "Hands on ROS for Robotics Programming" published by Packt Pub https://www.packtpub.com/iot-hardware/hands-on-ros-for-robotics-programming

## Folders `pkg_mygopigo` & `bagFiles`
Includes drives and distance sensor (to be added line follower and IMU)
- Source: [gopigo3_node](https://github.com/ros-gopigo/gopigo3_node)
- Folder `bagFiles` includes recorded sessions of distance sensor and Pi camera

## Pi Camera python: Folder `piCamera`
Sample python files to use the Pi Camera
>Source: [Recipes](https://picamera.readthedocs.io/en/release-1.13/recipes1.html)

## Pi Camera ROS: Folder `pkg_raspicam_node`
Manage Raspberry Pi Camera from ROS.
>Source [raspicam_node](https://github.com/UbiquityRobotics/raspicam_node)

Part of **chapter 6 Programming in ROS- Commands and Tools**

## YDLidar X4 ROS: Folder `ydlidar`
Manage EAI YDLidar X4 from ROS:
>Source [ydlidar](https://github.com/EAIBOT/ydlidar)

Part of **chapter 9 SLAM for Robot Navigation**

## Object recognition with Pi Camera: Folder `image_recognition`
Code of **chapter 10: Applying Machine Learning in
Robotics** to perform object recognition with the actual robot.