# Turtlebot3_pid_controller
```
A Simple PID Controller for TurtleBot3.
```
![sample_results](images/controls_gif1.gif)
![sample_results](images/controls_gif2.gif)

#Instructions
```
1. cd catkin_ws/src
```
```
2. git clone this repo
```
```
3. cd ..
```
```
4. catkin_make
```
```
5. roslaunch turtlebot3_gazebo turtlebot3_empty_world.launch
```
```
6. rosrun pid_control pid_control 
```

#Note
This doesnt have obstacle avoidance or local planner, just a very simple PID.


