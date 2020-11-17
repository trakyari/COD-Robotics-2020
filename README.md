# COD-Robotics-2020
Prereqs:

```
sudo apt-get install ros-noetic-gazebo-ros-pkgs ros-noetic-gazebo-ros-control
sudo apt-get install ros-noetic-ros-control ros-noetic-ros-controllers
sudo apt-get install ros-noetic-diff-drive-controller
sudo apt-get install ros-noetic-robot-state-publisher
```

Controller support prereqs

`sudo apt-get install xboxdrv`

2. ROS joy : http://wiki.ros.org/joy/Tutorials/ConfiguringALinuxJoystick

Starting the simulation with controller support

1. launch the simulation
2. `rosrun joy joy_node`
3. `rosrun simpleMod main.py`
