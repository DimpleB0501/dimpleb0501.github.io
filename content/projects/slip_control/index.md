---
title: "Slip Control Experimental Setup Design"
weight: 6
date: 2023-04-03
show_date: false
show_date_updated: false
reading_time: false
share: false

summary: "Tactile-sensor-based slip detection and grip control for robotic grasping."

tags:
  - Autonomous Robotics

tech_stack:
  - MATLAB
  - Simulink
  - Tactile Sensing
  - Slip Detection
  - Grip Control

links:
  - type: video
    url: "https://youtu.be/UbOTEKaXTJw"
    label: "YouTube"

featured: true
---

<figure>
    <img src="slip_control.png"
         alt="Slip control experimental setup">
    <figcaption>
        Figure: Slip control experimental setup
    </figcaption>
</figure>

<p align="justify">
To study the occurrence of slippage when mass is added to an object
gripped by a robotic end-effector, I designed an experimental setup to
recreate slip conditions and evaluate friction models developed by a
post-doctoral fellow.
</p>

<p align="justify">
I developed a high-density tactile sensor array designed to fit the
surface of the WidowX parallel gripper and built the associated
circuitry for acquiring tactile, force, and optical sensor data.
The sensing system was designed to acquire data at 0.01-second
intervals using Simulink.
</p>

<p align="justify">
The sensor measurements provided information about the magnitude and
direction of forces acting on the gripped object, which served as
inputs to the friction model and controller. I also developed an
interface for controlling the robot orientation and adjusting the
gripper position through micromotions at 0.01-second intervals.
</p>

<p align="justify">
These high-speed micromotions enabled the WidowX gripper to rapidly
adjust its grip once a slip event was detected by the friction
model and controller.
</p>
