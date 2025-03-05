# Kalman Filter and LQG Implementation

This project explores the implementation of the Kalman Filter and Linear Quadratic Gaussian (LQG) control for a 3D position-velocity system. These powerful tools are used in various applications including aerospace, robotics, autonomous vehicles, and navigation systems.

## Project Overview

This implementation demonstrates how to:

1. **Create a Kalman Filter** for state estimation in noisy environments
2. **Implement optimal control** using costate equations
3. **Combine these techniques** into an LQG controller
4. **Visualize results** with 3D trajectory plots and animations

## Technical Details

- **State Space Model**: The system is modeled with a 6-dimensional state vector (3D position and velocity)
- **System Dynamics**: Linear time-invariant dynamics with control inputs affecting acceleration
- **Observations**: Position measurements with added Gaussian noise
- **Cost Function**: Quadratic cost function balancing state deviation and control effort

## Key Features

- Complete implementation of all necessary Kalman Filter functions
- Solution to the Riccati equation for optimal control gain calculation
- Full LQG implementation combining state estimation and control
- Visualization tools including 3D trajectory plots and animations

## Usage

This notebook is designed as a walkthrough of these technologies, providing insights and practical implementations. It can be used as:

- An educational resource for understanding Kalman Filters and LQG control
- A starting point for implementing similar controllers in real-world applications
- A tool for experimenting with different system parameters and noise levels

## License

This project is licensed under the MIT License - see the LICENSE file for details. 