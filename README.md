# HomeWork 4 - Just practice some of ROS

## ROS architecture & philosophy

But first, the instruction can be found in [Programming for Robotics - ROS
](https://rsl.ethz.ch/education-students/lectures/ros.html) session 1. This HW represent the exercise from that session. 

Cloning this repo is not a good way to practice, so you have go to the page and follow this instruction yourself. This repo only contains the way I do this assignment. 

After following the first instrcution where I download the zip file and create workspace, I need to unzip the file in WSL Ubuntu 20.04
```
unzip smb_common.zip 
```

When running catkin_make there is an error with a missing package called "hector-gazebo-plugins" which can be install with: 
```
sudo apt-get install ros-noetic-hector-gazebo-plugins
```
then catkin_make 

## ROS master, nodes, and topics
run roscore on different terminal tap



## Console commands


## Catkin workspace and build system


## Launch-files


## Gazebo simulator