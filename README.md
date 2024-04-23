# HomeWork 4 - Just practice some of ROS

## ROS architecture & philosophy

But first, the instruction can be found in [Programming for Robotics - ROS
](https://rsl.ethz.ch/education-students/lectures/ros.html) session 1. 

This HW represent the exercise from the first session. 

This repo only contains the way I do this assignment, so all this is about how I did it and what are the problems I faced along the way. 

After following the first instructio where I download the zip file and create workspace, I need to unzip the file in WSL Ubuntu 20.04, so I use:
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

When trying to launch the package, I forgot that I need to specify the launch file 
```
roslaunch 
```

| Left   | Center  | Right  |
|:------:|:-------:|-------:|
| L0     | **bold**| $1600  |
| L1     | `code`  | $12    |
| L2     | _italic_| $1     |



## Console commands


## Catkin workspace and build system


## Launch-files


## Gazebo simulator