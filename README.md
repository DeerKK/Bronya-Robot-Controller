# Bronya-Robot-Controller
This is an QP-based robot controll framework, which is designed for torque-controlled robot. Core solver uses full dynamics model of the robot, applying whole body control (WBC) method to the robot.

Note that we differenciate the robot with 'torque-control' and 'position-control', which means their low-level joint controllers have 'torque' or 'position' as their inputs.

## Dependency
- Environment: Ubuntu, Python3
- Physical Engine: Vortex
- Robot Model: URDF
- Simulation: VREP
- Robotic Dynamics: Klampt
- Quadratic Programming: QPOASES

## Experiment
Currently we apply it to Tsinghua Walker robot, a adult-size humanoid robot. The framework works well in simulation.
