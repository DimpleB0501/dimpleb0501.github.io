---
title: "Lightweight Smart Sense-and-Avoid Module for Low-Altitude Agricultural UAVs"
weight: 1
date: 2023-04-03
show_date: false
show_date_updated: false
reading_time: false
share: false

card_link: "https://sense-and-avoid.github.io/"

summary: "Reactive, Plug-and-Play Sense-and-Avoid System for Pixhawk-Based UAVs in Precision Agriculture."

tags:
  - UAV Systems

tech_stack:
  - Python
  - ROS
  - Visual-Inertial Fusion
  - ArduPilot/ MAVLink
  - Real-Time Autonomous Navigation

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

  - type: pptx
    url: "/uploads/sense-n-avoid.pptx"
    label: "Presentation"

featured: true
---
<p align="justify">
This paper introduces a lightweight framework aimed at enhancing UAV operations
for low-altitude flight in agriculture fields. Farmlands are often filled with
obstacles such as trees, structures, and poles, that pose risks of collision
during low flying. To address this challenge, the proposed system combines
depth data from RGB-D camera with an IMU to generate LiDAR-like data, ensuring
seamless integration with any range sensor-based avoidance algorithms. The
entire perception and processing stack runs on the sense-and-avoid module,
which can be easily mounted on any MAVLink compatible flight controller. This
enables the UAV to detect and avoid obstacles in real time, smoothly
transitioning from semi-autonomous to fully autonomous flight mode. By
minimizing yaw during navigation, the system ensures flight efficiency and
stability, using only 40 % of the onboard processor capacity, leaving room for
the integration of additional functionalities, such as aerial spraying, data
collection, etc. The effectiveness of the system was validated through
simulations and real-world tests, showing reliable performance in diverse
agricultural settings. This sense-and-avoid technology has broad applications
in agriculture, surveillance, and disaster relief, improving UAV navigation in
obstacle-dense environments.
</p>
