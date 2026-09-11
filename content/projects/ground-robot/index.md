---
title: "Encoder-Orientation Sensor Fusion for Ground Robot Navigation"
date: 2024-09-20
show_date: false
show_date_updated: false
reading_time: false
share: false

summary: "Sensor fusion and velocity control for autonomous ground robot navigation and LiDAR-based obstacle avoidance."


tags:
  - Autonomous Robotics

tech_stack:
  - Python
  - ROS
  - MicroPython
  - Raspberry Pi Pico
  - NVIDIA Jetson Orin Nano
  - LiDAR
  - Sensor Fusion

links:
  - type: pdf
    url: "https://www.sciencedirect.com/science/article/pii/S2405896325024796"
    label: "Paper"

  - type: site
    url: "https://sense-and-avoid.github.io/"
    label: "Website"

  - type: video
    url: "https://www.youtube.com/watch?v=uHRtXmLqwPw"
    label: "YouTube"

featured: true
---
<p align='justify'>
To achieve autonomous navigation for a ground robot, I worked on the development of:
</p>

<ul>
  <li>Encoder-based low-level controller developed with Raspberry Pi Pico.</li>
  <li>Sensor fusion for robot localization using wheel encoders and orientation sensors.</li>
  <li>Velocity controller design for LiDAR-based obstacle avoidance using NVIDIA Jetson Orin Nano.</li>
</ul>

<figure>
    <img src="ground_robot.gif"
         alt="Autonomous ground robot navigation">
    <figcaption>Figure: Autonomous navigation and obstacle avoidance for ground robot</figcaption>
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
    The aim of this project was to develop a prototype rover that could be
    scaled for vineyard data collection. The velocity controller was also
    tested on a TurtleBot to validate the obstacle avoidance performance.
    </p>
  </div>
</div>
