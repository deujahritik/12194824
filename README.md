# 12194824

## **This readme file includes all the required steps followed and practice session's activities with Turtlesim and RQT, during the lab session of Week-4 Lecture.**

### - Installing the turtlesim 

*Firstly, the system was updated and the installation of turtlesim was done using the code below.*
```
sudo apt update
sudo apt install ros-rolling-turtlesim
```
![11](https://user-images.githubusercontent.com/92029196/192182768-074e5a2e-8f33-48f3-92f6-6d6d4d863684.png)


### - Starting and Running the Turtle
*The first command here opens the simulator windows with the turtle in the center and in order to control the turtle, the second command was used. Once the command is executed in the new terminal, the turtle was able to be controlled using the arrow keys and the path of movement was visible as shown in the image below. 
```
ros2 run turtlesim turtlesim_node
ros2 run turtlesim turtle_teleop_key
```
![Ritik_1](https://user-images.githubusercontent.com/92029196/192182325-5fd2d282-b29d-4595-b7eb-8b1cffbe303e.png)

![RunningTurtle](https://user-images.githubusercontent.com/92029196/192182401-c70ddf25-3ff0-49f8-ba88-8874d18d6d60.png)



### Installing rqt

*Similarly, the system was updated and the RQT packages were installed using the following commands.*

```
sudo apt update
sudo apt install ~nros-rolling-rqt*
```

### Running rqt
*To run rqt, simple 'rqt' command was executed and the following window appeared:*

### Starting rqt_console

```
ros2 run rqt_console rqt_console
```
*In the new terminal, the rqt_console command was executed with the above code and the new window that appeared is shown in the image here.*

![rqt_console](https://user-images.githubusercontent.com/92029196/192182463-8a8bcd3e-15d2-4a86-aa46-e55d8f896892.png)

### Spawn Scenario 
![Spawn Service](https://user-images.githubusercontent.com/92029196/192183251-868d7cb1-1496-4bbd-b15e-37efa9e65ccf.png)


### Stop Simulation 
Ctrl+C will stop the simulation easily. 
