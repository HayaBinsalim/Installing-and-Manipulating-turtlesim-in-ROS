# Installing-and-Manipulating-turtlesim-in-ROS

# Description 
This file will give the steps of installing ***turtlesim*** package in ROS Noetic on Ubuntu 20.4 and manipulating it with very simple steps. 
## 1. Installing turtlesim
In the ***terminal*** application in Ubuntu 20.4, run the following command to install ***turtlesim***
```
sudo apt update
sudo apt install ros-noetic-turtlesim
```
## 2. Running turtlesim 
To run ***turtlesim*** and ensure the installation was successful, you will have to launch it. In a new terminal, start the ROS master node by running 
```
roscore
```
Then, open another terminal and launch ***turtlesim*** using the following command:
```
rosrun turtlesim turtlesim_node
```
This should open the ***turtlesim*** simulator; you can see it in the image below. <br />

<img width="306" alt="image" src="https://github.com/HayaBinsalim/Installing-and-Manipulating-turtlesim-in-ROS/assets/173661622/ce79b0ff-6291-4c45-a0b0-f503a81a7f3c">


## 3. Controlling turtlesim 
To control turtlesim, or move the turtle, open a new third terminal and run the following command: 
```
rosrun turtlesim turtle_teleop_key
```
This will allow you to move the turtle around with the arrow keys in the keyboard. The movement of the turtle is shown by linear lines. An example is shown in the image below. <br />

<img width="306" alt="image" src="https://github.com/HayaBinsalim/Installing-and-Manipulating-turtlesim-in-ROS/assets/173661622/5b068076-6d81-4df6-8afc-6a9e78062941">

### Reference 
https://wiki.ros.org/turtlesim
