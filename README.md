# MCT511-Robot-Manipultor-Dynamics-and-Control
Robot manipulators are articulated mechanical systems composed of links connected by joints. In order to model the 2-DOF robot arm, we have to consider the kinematics and dynamics behaior of the robot in space.
The kinematics studies the motion of the bodies without consideration of the forces or moments that cause the motion. Robot kinematics refers to the analytical study of the motion of a robot manipulator. The robot kinematics can be divided into FORWARD and INVERSE kinematics. The forward kinematics desrcibes the relation between the joint position and the position and orientation of the robot's end-effector while the inverse kinematics consists precisely in the inverse relation of the forward kinematics model, that is, it corresponds to the relation between coordinate position vector and joint angular position. 
The dynamic model of a robot consists of an ordinary differential equation where the variable corresponds to the vector of positions and velocities, which may be in joint coordinates ir in operational coordinates. The dynamic equations of a robot manipulator can be obtained from Newton's equations of motion or, via Lagrange's equations. Here we considered a robot manipulator of 2 degrees of freedom (2-DOF) using the Lagrangian approach.
The 2-DOF robot is modeled in Simulink using simscape. We developed a control system for the robot to track a reference trajectory. The controller needs more robust tunning to optimally track the trajectory. feel free to use the and modify the code by simply folking this repository. 

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
