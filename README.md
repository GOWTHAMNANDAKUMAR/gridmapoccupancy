
# 2D Occupancy Gridmap Implementation

- This repository contains the implementation of a 2D occupancy grid mapping algorithm. The demonstration uses a Turtlebot in a Gazebo simulation environment.


## Run Locally/Usage

1. Launch the Turtlebot Demo World

To start the Turtlebot in the Gazebo environment, run the following command:

```
roslaunch mapping turtlebot_in_stage.launch
```
2. Run Occupancy Grid Mapping Node
To execute the occupancy grid mapping node, use this command:
```
roslaunch mapping mapping.launch
```
- This process uses ground truth data to localize the robot and update the map. This setup is designed to help you understand the basic implementation of occupancy grid mapping.

- For simultaneous localization and mapping (SLAM), which involves creating a map while localizing the robot, more advanced SLAM algorithms are used.
## Additional Information

Occupancy Grid Mapping: 

- This technique divides the environment into a grid of cells, each of which can be marked as free, occupied, or unknown. The robot uses sensor data to update these cells and build a map of the environment.

Turtlebot: 

- Turtlebot is a low-cost, personal robot kit with open-source software. It's widely used in education and research for understanding robotics concepts.

Gazebo: 

- Gazebo is a robust simulation tool that provides realistic environments for testing and developing robots without the need for physical hardware.

SLAM Algorithms: 

- SLAM stands for Simultaneous Localization and Mapping. Algorithms such as GMapping, Hector SLAM, and Cartographer are commonly used to enable a robot to build a map of an unknown environment while keeping track of its current position within that map.
## Installation Requirements


Ensure you have the following software installed:

1. ROS (Robot Operating System)
2. Gazebo
3. Turtlebot packages
4. Mapping packages
## Conclusion


- The 2D Occupancy Gridmap implementation provides a fundamental understanding of how robots perceive and map their environment using sensor data. By using Turtlebot in a Gazebo simulation, we demonstrated the process of creating a grid-based map, updating it with real-time data, and visualizing the robot's surroundings.

- This project serves as a stepping stone towards more complex autonomous navigation tasks. With further enhancements such as integrating advanced SLAM algorithms, improving visualization tools, and supporting various sensors and robots, this implementation can be extended to more robust and dynamic applications in real-world scenarios.

- Through this project, we have explored the critical aspects of occupancy grid mapping, paving the way for further research and development in the field of robotics and autonomous systems.
## Authors

- [@GowthamNandakumar(Github)](https://github.com/GOWTHAMNANDAKUMAR)

- [@GowthamNandakumar(LinkedIn)](https://www.linkedin.com/in/gowtham-nandakumar-578625254/)
