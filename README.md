# RoboticsNanodegree

This is a repository containing code written for Udacity's Robotics Software Engineer Nanodegree. It contains projects developed for the Nanodegree. Projects are desinged to be run in a ROS Catkin workspace, and have been tested on ROS Kinetic.

## Project 1 - Build My World

This project is an introduction to Gazebo, and contains a Gazebo World and a few models designed for that world. Dogbone World is a house with a few rooms and two tables shaped roughly like dog bones. A additional blocks of various shapes and sizes were added to the world to act as landmarks. These blocks were used rather than Gazebo model objects because the pgm-map-creator package that is used later to generate a map of the world does not perform well with Gazebo models of irregular shapes.

### Simple steps to interact with a World in Gazebo through a World plugin

#### 1- Create a directory for scripts inside “sal_bot” to store a salman_hello.cpp file

#### 2- Create a CMakeLists.txt file

#### 3- Create a build directory and compile the code

$ mkdir build

$ cd build/

$ cmake ../

$ make # You might get errors if your system is not up to date!

$ export GAZEBO_PLUGIN_PATH=${GAZEBO_PLUGIN_PATH}:/home/workspace/sal_bot/build

#### 4- Open your world file and attach the plugin to it

#### 5- Launch the world file in Gazebo to load both the world and the plugin



