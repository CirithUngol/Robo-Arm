# Robotic_Arm_ROS

ROS Version: Kinetic<br/>
Gazebo Version: 7.0.0

### To Run:
1. Download and put the folder Robotic_Arm_ROS/catkin_ws/src/myarm_plugin in your Catkin workspace.
2. Delete the contents of build folder.
3. cd into build folder and type: cmake ../
4. Once it finishes, type: build
5. Now start ros server: roscore
6. And start gazebo: gazebo ../myarm.world
7. In a new terminal, start a rostopic and provide float values to control the velocity. 
