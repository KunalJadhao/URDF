My Robot URDF Project

This project contains a Unified Robot Description Format (URDF) model of my custom robot.
It is designed for simulation in ROS 2 with RViz and Gazebo.
The URDF describes the robot’s physical structure, joints, and visual elements for use in virtual testing and development.


📌 Features

    Custom Robot URDF with links, joints, and meshes.

    Visual and collision models for realistic simulation.

    Configured to work with ROS 2 and RViz.

    Gazebo integration for physics-based simulation.
    
Project Structure

My_robot_controller/
├── urdf/
│   ├── my_robot.urdf          # Main URDF file
│   ├── my_robot.gazebo        # Gazebo-specific tags (optional)
│   ├── meshes/                # 3D model files (STL/DAE)
│   └── materials.xacro        # Material and color definitions
├── launch/
│   ├── display.launch.py      # Launch file for viewing in RViz
│   └── gazebo.launch.py       # Launch file for running in Gazebo
├── package.xml                # ROS 2 package info
└── CMakeLists.txt             # Build instructions

🛠 Requirements

    ROS 2 (e.g., Humble or Foxy)

    RViz 2

    Gazebo (optional but recommended for physics simulation)

    Ubuntu 20.04+
