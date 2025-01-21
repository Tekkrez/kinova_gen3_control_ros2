# Kinova gen3 control in ROS2 using Kinova Kortex API
Launch nodes using the following command to start the desired position to joint velocity controller
```
ros2 launch move_it_node moveit_vel_control_node.launch.py
```
Run the following command to control the robot based on desired joint velocities
```
ros2 run gen3_control gen3_vel_control
```

Run the following command to start the VR controller and headset position to desired end effector position interface
```
ros2 launch vr_manager pose_viz.launch.py
```
