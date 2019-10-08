# Udacity_project1
# This project aims to build own world

# Directory Structure
$    Project1                          # Build My World Project 
$    ├── model                          # Model files 
$    │   ├── Building
$    │   │   ├── model.config
$    │   │   ├── model.sdf
$    │   ├── HumanoidRobot
$    │   │   ├── model.config
$    │   │   ├── model.sdf
$    ├── script                         # Gazebo World plugin C++ script      
$    │   ├── welcome_message.cpp
$    ├── world                          # Gazebo main World containing models 
$    │   ├── UdacityOffice.world
$    ├── CMakeLists.txt                 # Link libraries 
$    └──             

Gazebo in workspace
- Before launching Gazebo
$ sudo apt-get update && sudo apt-get upgrade -y 
$ gazebo
