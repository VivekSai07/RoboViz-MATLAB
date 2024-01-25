# RoboViz: MATLAB Robotics Visualization Tool

## Overview
RoboViz is a MATLAB-based robotics visualization tool that empowers users to effortlessly visualize and analyze robotic arms with varying degrees of freedom (DOF). Whether you want to input your Denavit-Hartenberg (DH) parameters manually or choose from a selection of predefined robots, RoboViz provides an intuitive interface for 3D visualization and analysis.

## Features
**1. Choose Your Robot**
- Enter DOF: Manually input DH parameters for a customized robotic arm, ranging from a simple 2-link arm to a complex 10-link arm.
- Choose Robot: Select from a set of predefined robots with default DH parameters for quick visualization.

**2. 3D Visualization**
- Interactive Plotting: Visualize the robotic arm in 3D space, allowing you to rotate, pan, and zoom for a comprehensive view.
- End-Effector Coordinates: Instantly view the coordinates (X, Y, Z) of the end-effector for precise analysis.

**3. Work Envelope Visualization**
- Envelope Display: Explore the work envelope of the robot by clicking on the dedicated button, providing insights into the reachable space.

## Sample Example
- **2 DOF**
<p align="center">
  <img src="https://github.com/VivekSai07/RoboViz-MATLAB/blob/main/2%20DOF.png" width="700" alt="2DOF">
  <img src="https://github.com/VivekSai07/RoboViz-MATLAB/blob/main/2%20DOF%20(workspace).png" width="700" alt="2DOF">
</p>
<!-- ![2 DOF](https://github.com/VivekSai07/RoboViz-MATLAB/blob/main/2%20DOF.png) -->

- **Cartesian Robot**
<p align="center">
  <img src="https://github.com/VivekSai07/RoboViz-MATLAB/blob/main/Cartesian%20robot.png" width="700" alt="Cartesian Robot">
  <img src="https://github.com/VivekSai07/RoboViz-MATLAB/blob/main/Cartesian%20robot%20(workspace).png" width="700" alt="Cartesian Robot Workspace">
</p>

- **Cylindrical Robot**
<p align="center">
  <img src="https://github.com/VivekSai07/RoboViz-MATLAB/blob/main/Cylindrical%20Robot.png" width="700" alt="Cylindrical Robot">
  <img src="https://github.com/VivekSai07/RoboViz-MATLAB/blob/main/Cylindrical%20Robot%20(workspace).png" width="700" alt="Cylindrical Robot Workspace">
</p>

## Getting Started
1. Clone the repository:
```bash
git clone https://github.com/VivekSai07/RoboViz-MATLAB.git
```
2. Open MATLAB and navigate to the project directory.
3. Run the **RoboVizApp.mlapp** file.
4. Choose your preferred robot or enter DH parameters as per your requirements.
5. Visualize the robot in 3D, inspect end-effector coordinates, and explore the work envelope.

## Dependencies
- MATLAB R2023a or later.

## Contribution Guidelines
We welcome contributions! If you have ideas for improvements or new features, please open an issue or submit a pull request.

## Acknowledgments
- MATLAB - The platform that made this project possible.

Feel free to explore, experiment, and contribute to enhance RoboViz. Happy coding!
