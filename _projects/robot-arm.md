---
layout: page
title: Robot Arm 
description: Building an autonomous robot arm to do different tasks at ARC
img: assets/img/robot-arm/assets/img/obj_det_may_21.png  
importance: 4
category: clubs
---

> [GitHub](https://github.com/purdue-arc/arc_robot_arm)

## Overview 

The goal is to explore why robots are limited to factory environments and why we don't have them cooking for us  and folding our clothes yet. The current task is to get the arm to play chess. My contributions are the following:

### May 2021

- Object detection working on chess pieces with 90%+ accuracy using YOLOv5 and usable in ROS
  - Put together a 500+ chess piece dataset for detection

{% include figure.html path="assets/img/robot-arm/assets/img/obj_det_may_21.png" title="object detection" class="img-fluid rounded z-depth-1" %}

- Created Gazebo simulation that is controlled by MoveIt pipeline, including a simulated camera, chessboard, and chess pieces

{% include gd_player.html id="19FZ7lsqCn6DEChjjdBgsTy0feUANYaVO" %}

### December 2020

- Box stacking using inverse kinematics and motion planning using MoveIt and ROS

{% include gd_player.html id="1yms3OuqYp-n4JCt-yBGZg8yEyajXOj_M" %}