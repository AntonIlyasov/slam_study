0. source devel/setup.bash
1. roslaunch tb3_nav slam.launch
2. roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch
3. сохранить карту - rosrun map_server map_saver -f ~/map
4. автономное предотвращение столкновений - roslaunch turtlebot3_gazebo turtlebot3_simulation.launch



killall gzserver gzclient roslaunch rosmaster
