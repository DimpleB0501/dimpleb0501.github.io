---
title: "Encoder-Orientation Sensor Fusion for Ground Robot Navigation"
weight: 7
date: 2023-04-03
show_date: false
show_date_updated: false
reading_time: false
share: false

summary: "Sensor fusion and LiDAR-based obstacle avoidance for autonomous ground robots."

tags:
  - Autonomous Robotics

tech_stack:
  - Python
  - ROS
  - MicroPython
  - Sensor Fusion
  - LiDAR based obstacle avoidance

links:
  - type: video
    url: "https://youtu.be/YzKCNNOa5m0"
    label: "YouTube"

featured: true
---
<p align="justify">
This project focused on developing the core sensing, control, and navigation
components for an autonomous ground robot, including:
</p>

<ul>
  <li>
    <b>Low-level control:</b> Developed an encoder-based motor controller
    using a Raspberry Pi Pico and MicroPython.
  </li>

  <li>
    <b>Localization:</b> Fused wheel encoder and orientation sensor data
    to estimate the robot's motion and orientation.
  </li>

  <li>
    <b>Obstacle avoidance:</b> Developed a velocity controller using LiDAR
    data and deployed it on an NVIDIA Jetson Orin Nano for autonomous
    obstacle avoidance.
  </li>
</ul>

<figure>
    <img src="ground_robot.gif"
         alt="Autonomous ground robot navigation">
    <figcaption>
        Figure 1: Autonomous ground robot navigation and obstacle avoidance
    </figcaption>
</figure>

<div style="clear: both;">
  <div style="float: right; margin-left: 1em; margin-top: -40px">
    <figure>
        <img src="turtlebot.gif"
             alt="TurtleBot obstacle avoidance"
             width="300">
        <figcaption>Figure 2: Obstacle avoidance with TurtleBot</figcaption>
    </figure>
  </div>

  <div>
    <p align='justify'>
    The system was developed as a prototype for autonomous vineyard
    data collection. The LiDAR-based velocity controller was additionally
    evaluated on a TurtleBot to validate its obstacle avoidance performance.
    </p>
  </div>
</div>
