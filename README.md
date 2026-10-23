🚙 Differential Drive Robot Simulation (ROS 2 Humble + Gazebo Harmonic)

# Differential-Drive-Robot
A simulation of a custom differential-drive robot named Rickshaw, modeled in URDF/XACRO, simulated in Gazebo Harmonic, and visualized in RViz 2. This project demonstrates integration of ROS 2 Humble with Gazebo Harmonic using the ros_gz_bridge.


 🧩 Project Overview
Features

    ✅ Fully defined robot model using XACRO
    ✅ Simulated in Gazebo Harmonic
    ✅ Visualization in RViz 2
    ✅ ROS–Gazebo communication via ros_gz_bridge
    ✅ Automated robot spawning and topic bridging through launch file
📂 Package Structure

my_robot/ ├── CMakeLists.txt ├── package.xml ├── launch/ │ └── display.launch.xml ├── model/ │ ├── my_robot.urdf.xacro │ ├── materials.xacro │ └── gazebo.urdf.xacro ├── gazebo/ │ └── test_world.sdf ├── config/ │ └── parameter_bridge.yaml └── Rviz2/ └── Rviz.rviz



⚙️ Dependencies

Ensure the following are installed:

sudo apt install ros-humble-xacro ros-humble-ros-gz-bridge \
ros-humble-ros-gz-sim ros-humble-robot-state-publisher \
ros-humble-joint-state-publisher-gui ros-humble-rviz2
