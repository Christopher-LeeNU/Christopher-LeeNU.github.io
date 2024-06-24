---
layout: page
title: DS (Da Snake)
permalink: /engineering/DS
---



In this project, I designed a yoshimura pattern soft robot to be controlled by a Nintendo DS. I worked on this in conjunction with Graham Grieb, and you can check out his amazing work on the DS controls and livestreaming capabilities on this [GitHub Page](https://github.com/grahamgrieb/DSi-Robot).

## Design and Construction
Inspired by methods described in [this video from the University of Southern Denmark](https://www.youtube.com/watch?v=lVxFdTldYxw), the body of the robot was constructed using laser-cut cardboard. The main body was modeled in Solidworks, and multiple iterations were required to achieve controlled motion.

![dsside](/assets/img/ds/dsside.jpg)

### Key Features:

![dsside](/assets/img/ds/dsside.jpg)

Material and Structure: The robot's body is made from laser-cut cardboard, with precise control over material thickness at the creases to manage stiffness.
Actuation: The robot is powered by two DC motors, controlled via simple PWM through a motor driver. These motors expand and contract strings connecting the front and rear of the robot. This setup enables the robot to move forward and turn left or right.
Traction and Balance: High-friction rubber coatings on the front and rear sections ensure proper ground traction. The "face" and motors are balanced in weight to maintain stability.


## Control System
The robot is controlled using a Nintendo DS, with the DS's camera capturing images and sending them to the robot's LCD screen via a WiFi WebSocket. This innovative use of the DS not only controls the robot's movement but also enhances interactivity by providing real-time visual feedback.

