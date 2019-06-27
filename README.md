# RoboND P0 Build My Own World!

![gazebo](https://user-images.githubusercontent.com/48291391/60264550-78831280-98b1-11e9-9720-bf643ff97992.png)

## Overview

In this project I create a simulation world in **Gazebo** which interacts with **World Plugins** for all my following projects in the Udacity Robotics Software Engineer Nanodegree Program.

  1. A single-floor Apartment is built using the **Building Editor tool** in Gazebo with color and texture features to the structures. 
  2. A 3-dof revolute-joint Robotic Manipulator prototype and a simplified mobile robot mounted with Hokuyo Laser Sensor are created        using **the Model Editor tool** in Gazebo. 
  3. Quadrotor and other models are imported from the Gazebo Online Library inside an empty Gazebo world.
  4. A  C++ "Welcome" message from **World Plugin** is generated to inform the interactaction with your world.

## Directory Strcture
The sample simulation world folder has the following directory structure:

    .Project1                          # Build My World Project 
    ├── model                          # Model files 
    │   ├── Building
    │   │   ├── model.config
    │   │   ├── model.sdf
    │   ├── HumanoidRobot
    │   │   ├── model.config
    │   │   ├── model.sdf
    ├── script                         # Gazebo World plugin C++ script      
    │   ├── welcome_message.cpp
    ├── world                          # Gazebo main World containing models 
    │   ├── UdacityOffice.world
    ├── CMakeLists.txt                 # Link C++ code to libraries 
    └──            


