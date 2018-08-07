# edo_gazebo
Comau e.DO Gazebo Simulation

To start the simulation use the following commands:

```
roscore
roslaunch edo_gazebo edo.launch
roslaunch edo_moveit edo_moveit_planning_execution.launch sim:=true
roslaunch edo_moveit moveit_rviz.launch config:=true
```

You may need to use the [eDO_description](https://github.com/Pro/eDO_description) repository from my fork.

