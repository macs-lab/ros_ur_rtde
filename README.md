# ros_ur_rtde
This ROS package provide useful Python scripts for building connection to UR robot via RTDE protocal. 

The scripts are provided by UR, please refer to their [documentation](https://www.universal-robots.com/how-tos-and-faqs/how-to/ur-how-tos/real-time-data-exchange-rtde-guide-22229/).

Dowlaoad and compile the package, then you can import the rtde class to your ROS node:
```
import ur_rtde.rtde as rtde
import ur_rtde.rtde_config as rtde_config
import rospy
...
```
