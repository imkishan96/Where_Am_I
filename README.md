# Where_Am_I
ros pkg for udacity project Where Am I?  
**NOTE**: rename the folder Where_Am_I to my_robot
## install
```
cd catkin_ws/src
git clone https://github.com/imkishan96/Where_Am_I.git
```
rename the folder `Where_Am_I` to `my_robot`
```
mv ~/catkin_ws/src/Where_Am_I ~/catkin_ws/src/my_robot
```
build and source
```
cd ..
catkin_make
source devel/setup.bash
```

## launch
```
cd catkin_ws
source devel/setup.bash
roslaunch my_robot world.launch
```
click on the terminal and use the following keys to control the robot
```
      U   I   O 
      J   K   L 
      M   <   > 
```
![GitHub Logo](/bot_rviz.png)
[ successful localization  ]
