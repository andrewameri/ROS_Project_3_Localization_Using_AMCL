# Localization with AMCL

This project was done as part of assignments in Udacity Sofware Engineer Nanodegree. In this project, we utilize ROS AMCL package to accurately localize a mobile robot inside a map in the Gazebo simulation environments.

### Prerequisites

This project has been written and tested in Ubuntu 16.04LTS using ROS Kinetic. 

### Installing

1- Clone the project and make sure to place the "where_am_i" folder in src folder of your catkin_ws

```
$ git clone https://github.com/andrewameri/ROS_Project_3_Localization_Using_AMCL.git
```
2- Go back to catkin_ws folder and make the project

```
$ cd ..
$ catkin_make
```

## Running the tests

1- Launch the nodes 
```
$ roslaunch where_am_i world.launch
$ roslaunch where_am_i amcl.launch
```
2- Use teleop node to control the robot and observe it localize itself in the environment
```
$ rosrun teleop_twist_keyboard teleop_twist_keyboard.py
```


## Authors

* **Udacity** - *Initial code snippets * - [Udacity](https://www.udacity.com)
* **Andrew Ameri** - *Finalizing, building, and testing the project* - [andrewameri](https://github.com/andrewameri)



