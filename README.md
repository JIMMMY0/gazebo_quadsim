Gazebo Quadrotor Simulator (hardware-in-the-loop)
=============================

**This project is a part of [StarryPilot](https://github.com/JcZou/StarryPilot) autopilot software**

![](gazebo.png)

# Usage
The simulator is tested in **ROS kinetic**, for other distributions, it is not well tested.
- *Compile packages*

In ROS workspace, execute `catkin build`

- *Launch mavros*

`roslaunch mavros starry.launch`

- *launch gazebo* 

`roslaunch rotor_gazebo starry_hil_launch`

To execute the simulation, you should set [**StarryPilot**](https://github.com/JcZou/StarryPilot) autopilot firmware to **HITL mode**.
