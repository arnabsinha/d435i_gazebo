# Intel RealSense Gazebo ROS plugin

This package is a Gazebo ROS plugin for the Intel D435i realsense camera. Through this package, one can run the D435i camera (in simulation) with a urdf/xacro files included within a launch flile.

This package has been developed and tested in ROS Melodic, Ubuntu 18.04.

How to RUN:
1. within catkin workspace go to srcc directory and clone this package.
2. go to your catkin workspace and do "catkin build".
3. after successful compilation, run the following commands:
	a) source devel/setup.bash
	b) roslaunch d435i_gazebo test_urdf.launch
 
## Acknowledgement

This is a continuation of work done by [SyrianSpock](https://github.com/SyrianSpock) for a Gazebo ROS plugin with RS200 camera.

This package also includes the work developed by Intel Corporation with the ROS model fo the [D435](https://github.com/intel-ros/realsense) camera.

Finally this package is also  dependent on the work done by [Pal-Robotics](https://github.com/pal-robotics/realsense_gazebo_plugin).

# d435i_gazebo
