# edo_gazebo
Comau e.DO Gazebo Simulation

To start the simulation use the following commands:

Only the robot:

```
roscore
roslaunch edo_gazebo edo.launch
roslaunch edo_moveit edo_moveit_planning_execution.launch __ns:=edo sim:=true
roslaunch edo_moveit moveit_rviz.launch __ns:=edo config:=true
```

Robot with Gripper:

```
roscore
roslaunch edo_gazebo edo_gripper.launch
roslaunch edo_gripper_moveit edo_moveit_planning_execution.launch __ns:=edo sim:=true
roslaunch edo_gripper_moveit moveit_rviz.launch __ns:=edo config:=true
```

You may need to use the [eDO_description](https://github.com/Pro/eDO_description) repository from my fork.

