 #AlohaMini_Simulation
 
 AlohaMini Simulation includes the visualization of AlohaMini by rviz in ROS1/2.

source install/setup.bash
# 切换到 FastDDS
export RMW_IMPLEMENTATION=rmw_fastrtps_cpp
# 然后测试
ros2 launch Aloha display.launch.py
