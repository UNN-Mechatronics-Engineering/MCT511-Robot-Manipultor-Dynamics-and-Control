# Robot Manipulator Kinematics and Dynamics

Welcome to the Robot Manipulator Kinematics and Dynamics! In this project, we explore the fascinating world of robot manipulators, which are articulated mechanical systems composed of links connected by joints. Our primary focus is on a 2-DOF robot arm, and we delve into the kinematics and dynamics that govern its behavior in space.

## Table of Contents
- [Introduction](#introduction)
- [Kinematics](#kinematics)
  - [Forward Kinematics](#forward-kinematics)
  - [Inverse Kinematics](#inverse-kinematics)
- [Dynamics](#dynamics)
  - [Dynamic Model](#dynamic-model)
- [Solidworks model](#solidworks-model)
- [Simulation and Control](#simulation-and-control)
- [Resources ](#resources)

## Introduction

Robot manipulators are fascinating machines that mimic the movement and control of human arms. These systems are crucial in various industries, including manufacturing, healthcare, and robotics. In this repository, we focus on a 2-degree-of-freedom (2-DOF) robot arm and examine its behavior through mathematical models and simulations.

## Kinematics
![forwardinverse](https://github.com/UNN-Mechatronics-Engineering/MCT511-Robot-Manipultor-Dynamics-and-Control/assets/63534670/beb070b6-53e2-485f-991c-be7ce5af4e99)

### Forward Kinematics

The kinematics of a robot arm study the motion of its components without considering the forces or moments that drive that motion. We specifically delve into robot kinematics, which is the analytical study of how a robot manipulator moves. The forward kinematics helps us understand the relationship between the joint positions and the position and orientation of the robot's end-effector.

### Inverse Kinematics

Conversely, the inverse kinematics is all about finding the inverse relationship of the forward kinematics model. It relates the coordinate position vector to the joint angular positions. Understanding both forward and inverse kinematics is essential for controlling and navigating robot arms.

## Dynamics
![dyna](https://github.com/UNN-Mechatronics-Engineering/MCT511-Robot-Manipultor-Dynamics-and-Control/assets/63534670/f22c034c-4e8e-4f82-9288-919d05ed5c58)

### Dynamic Model

The dynamic model of a robot arm can be described by an ordinary differential equation, where the variables correspond to the vector of positions and velocities. These variables can be represented in joint coordinates or operational coordinates. We derive the dynamic equations of our 2-DOF robot manipulator from either Newton's equations of motion or Lagrange's equations, utilizing the Lagrangian approach.

## Solidworks Model
![soo](https://github.com/UNN-Mechatronics-Engineering/MCT511-Robot-Manipultor-Dynamics-and-Control/assets/63534670/afa56d14-27aa-4d5c-8f27-1bdc7467cffb)

The robotic arm was designed in Solidworks in parts and assembly, as can be extracted from the Solidworks folder to visualize the concept.

## Simulation and Control
![cont](https://github.com/UNN-Mechatronics-Engineering/MCT511-Robot-Manipultor-Dynamics-and-Control/assets/63534670/0a5b1130-2785-48e5-94ca-b02a38c535b6)

To bring our 2-DOF robot to life, we model it using Simulink with simscape. We have also developed a control system to enable the robot to track a reference trajectory. However, the controller might need further tuning to optimally track the trajectory. We encourage you to get involved and help us improve the code by forking this repository.

We hope you find the information and resources in this repository valuable as you explore the intriguing world of robot manipulator kinematics and dynamics. Join us in this journey of discovery and innovation!

## Resources
[1] Control of Robot Manipulators in Joint Space by R. Kelly, V. Santibanez, and A. Loria
[2] May 2017 preprint of Modern Robotics, Lynch and Park, Cambridge U. Press, 2017. http://modernrobotics.org
