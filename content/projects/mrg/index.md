---
title: Marine Robotics Group
date: 2023-03-29
description: "Reducing IMU drift with a 6-axis arm and deep learning"
summary: "Reducing IMU drift with a 6-axis arm and deep learning"
---

I'm doing a UROP (undergraduate research) at the MIT Marine Robotics Group this semester. I'm trying to reduce drift for Inertial Measurement Units (IMUs) commonly used in underwater robots. My plan is to attach research-grade IMUs to a six-axis arm and simulate random robot movement. By comparing where the arm thinks it is with where the IMU thinks it is, I can train a machine learning model to reduce error in the IMUs.

These are the IMUs I am using.
![IMUs](images/imus.jpg)

This is my 6-axis robot, who I've named Armin.
![Armin](images/armin.jpg)

I installed Ubuntu 18.04 on a laptop and setup ROS melodic and MoveIt to control the arm. Armin's got moves!
{{<youtube US2L-SOqrEw>}}