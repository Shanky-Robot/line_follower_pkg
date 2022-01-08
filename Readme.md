## Line Folloer Turtlebot3 


Project forked from:
https://github.com/DougUOW/line_follower_pkg

## To build
To build the project run the following steps in a terminal:
* Creating a catkin workspace:
```
mkdir catkin_ws
cd catkin_ws
mkdir src
catkin_make
```
* Cloning the repository and building:
```
cd ~/catkin_ws/src
git clone https://github.com/sudrag/line_follower_turtlebot.git
cd ..
catkin_make
```

## To run
To run the project and see the output in the gazebo world , execute the following steps:
```
cd ~/catkin_ws
source devel/setup.bash
export TURTLEBOT3_MODEL=waffle
roslaunch line_follower_pkg yellow_line_world.launch
rosrun line_follower_pkg follower_script.py
```

