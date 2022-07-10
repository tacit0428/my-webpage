---
slides: example
url_pdf: ""
summary: ""
url_video: ""
date: 2022-07-10T14:08:14.653Z
external_link: ""
url_slides: ""
title: Control Strategies of Path Tracking Problem for Autonomous Driving
tags:
  - Reinforcement Learning
  - Automatic Driving
  - Path Tracking
links: []
image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart
url_code: ""
---
Build the vehicle kinematics model and dynamics model. Realized LQR controller and MPC controller based on the vehicle models to control the vehicle motion following the track.
Introduced differentiable MPC algorithm and applied it to realize lateral control of the vehicle. PID controller was used as the longitudinal controller.
Compared four controllers based on their performance of path tracking problem in CARLA simulator.