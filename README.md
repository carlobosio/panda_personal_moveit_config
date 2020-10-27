# panda_personal_moveit_config

Clone this directory in the * *move_it* * workspace.
Before launching the packages, be sure to have cloned the * *franka_description* * directory (inside your franka_ros directory overwriting the existing one).
Write in a new terminal:
```
source ~/<name of your move_it_workspace>/devel.setup.bash 
roslaunch franka_description panda_gazebo.launch
```

and in a new terminal:
```
roslaunch franka_description rviz_moveit.launch
```
