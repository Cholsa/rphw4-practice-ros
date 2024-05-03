# HomeWork 4 - Just practice some of ROS with SMB robot (smb_common)

Easy copy and past for my machine

```
cd assignments/rphw4-practice-ROS/catkin_ws 

```

```
roslaunch smb_gazebo smb_gazebo.launch

```

```
roslaunch smb_control control.launch

```


# Issues I faced along the way 

## unzip files in WSL ubuntu

But first, the instruction can be found in [Programming for Robotics - ROS
](https://rsl.ethz.ch/education-students/lectures/ros.html) session 1. 

This HW represent the exercise from the first session. 

This repo only contains the way I do this assignment, so all this is about how I did it and what are the problems I faced along the way. 

After following the first instructio where I download the zip file and create workspace, I need to unzip the file in WSL Ubuntu 20.04, so I use:
```
unzip smb_common.zip 

```

## missing pluging

When running catkin_make there is an error with a missing package called "hector-gazebo-plugins" which can be install with: 
```
sudo apt-get install ros-noetic-hector-gazebo-plugins

```
then catkin_make 

Well, it appears that I have to watch the video to learn. 

## missing plugin 2

This time I need to set up velodyne_description

```
sudo apt-get install ros-noetic-velodyne-description 

```
