# ROS

```shell
# Create workspace
mkdir -p ~/catkin_ws/src
cd ~/catkin_ws/src
catkin_init_workspace

cd ~/catkin_ws
catkin_make

source devel/setup.bash
```

```shell
# Create package
cd ~/catkin_ws/src
catkin_create_pkg PACKAGE rospy
```

```shell
roscd deu_car
source ./gazebo_env.sh
chmod +x ./scripts/blocking_bar_control.sh
chmod +x ./scripts/obstacle_spawn.py
roslaunch deu_car car_test.launch
```

```shell
++ 추가 작성함. ++
깃허브 & pycharm 연동 참고 사이트 : https://seong6496.tistory.com/147
신호등 참고 사이트 : https://github.com/ser94mor/self-driving-car-using-ros
```
