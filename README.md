# lumi_testbed

Built by [Intelligent Robotics group](http://irobotics.aalto.fi).

The set of core ROS packages for lumi robot. Contains URDF description,  moveit configuration, mujoco configuration.

## Launch robot
Simulated robot without MuJoCo and MoveIt:
```sh
roslaunch lumi_description show.launch 
```

Simulated robot with MuJoCo and MoveIt:
```sh
roslaunch lumi_mujoco simulation.launch
```

A Simulation for affordance_gym with MuJoCo and MoveIt:
```sh
roslaunch lumi_mujoco table_simulation.launch
```

A Simulation for affordance_gym with Kinect, MuJoCo and MoveIt:
```sh
roslaunch lumi_mujoco table_simulation.launch
```

Real robot:
```sh
TBA. 
```
