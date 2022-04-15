---
layout: page
title: Robot Bandaging
description: Building a 2D cloth manipulation system for robots
published: true 
importance: 3
category: research 
---
### Overview
The multi-semester project goal is to develop manipulation policies and perception system to allow a robot to apply a medical bandage to a hand.

### Fall 2021 

#### State Estimation
The main goal was to explore robust object representations for the bandage. Implemented use of dense visual descriptors [^1] and **contrastive learning** explore generalization across various colors and states of the bandage.

{% include gd_pdf.html id="1Iu-oC3Ww0lPLtuP0n0b4cYQSFy-7weFv" %}


#### Visuo-Tactile Feedback 
Preliminary data was collected using a visuo-tactile gripper on a cloth, exploring the contact shear stresses over time as a feedback signal for keeping the bandage within grasp. The data shown was slowly moving a bandage through a parallel-jaw gripper with a visuo-tactile sensor.

{% include gd_player.html id="14KDckDlQPEpLXb9ABH7D8vNec-3XeJ8n" %}


[^1]: Florence, P., Manuelli, L., and Tedrake, R. Dense object nets: Learning dense visual object descriptors by and for robotic manipulation. Conference on Robot Learning, 2018.