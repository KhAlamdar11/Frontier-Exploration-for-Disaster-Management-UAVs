# Capstone-2D-exploration-stack

This ROS package provides a 2D frontier exploration stack for autonomous navigation of UAVs. It includes frontier extraction, candidate point generation, path planning (A*) and motion planning modules.
The motion planning module is interfaced with Pixhawk (PX4) controller.
The entire package is modular in nature and path planning or motion planning modules can be easily replaced as per need.
Input topics: Occupancy Grid and Pose of the UAV
