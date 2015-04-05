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

 * The driver has been update to support a wider range of neato models and firmware versions including the Neato's Botvac line.
 * This ROS node works with Indigo. The required third parameter to rospy.Publisher() has been supplied.
 * This fork is used with a Botvac 75 on Ubuntu. Running  a Rapsberry Pi 2 with Ros ARMF with Ubuntu ARFM on the Neato
   and all processing done by the workstation pc with ubuntu 14.04