# RobotND - Go Chase It

This is the second project for the Udacity [Robotics Software Engineer](https://www.udacity.com/course/robotics-software-engineer--nd209) course. The objective of this project is to build a robot that chases after a white ball.

![](images/image1.png 'image1')

## How to build
```
mkdir -p catkin_ws/src
cd catkin_ws
cp -r ../RobotND-Go_Chase_It/* src/
catkin_make
```

## How to run
Open a terminal and run the following
```
cd <path to catkin>/catkin_ws/
source devel/setup.bash
roslaunch my_robot world.launch
```

Open a new terminal and run the following
```
cd <path to catkin>/catkin_ws/
source devel/setup.bash
roslaunch ball_chaser ball_chaser.launch
```
