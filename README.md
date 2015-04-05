## Neato Drivers

This repository contains ROS drivers for Neato's robotic vacuums. 

## Usage
You can check this out into your catkin workspace as follows:

    roscd
    cd src
    git clone https://github.com/kcneato/neato_robot.git
    cd ..
    rosdep update
    rosdep install neato_robot
    catkin_make

## Changes in this fork

 * This fork is used with a Botvac 75 on Ubuntu 14.04. Running a Rapsberry Pi 2 with Ros ARM with Ubuntu ARF on the       Neato and all processing done by the workstation pc with ubuntu 14.04
