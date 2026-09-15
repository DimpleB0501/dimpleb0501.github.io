---
title: "Path Planning and Patrolling for a Team of Car-like Robots in a Campus Environment"
weight: 5
date: 2023-04-03
show_date: false
show_date_updated: false
reading_time: false
share: false

summary: "Vehicle-aware path planning and obstacle avoidance for multi-robot patrolling."

tags:
  - Autonomous Robotics

tech_stack:
  - Python
  - ROS
  - Webots
  - Path Planning
  - Multi-Robot Systems

links:
  - type: video
    url: "https://youtu.be/v_xDohm0imE"
    label: "YouTube"

featured: true
---

<p align="justify">
During my tenure at the Autonomous Robotics and Multi-Robot Systems
Lab at the Indian Institute of Technology Bombay, I worked on a
collaborative project with the Centre for Artificial Intelligence and
Robotics, Defence Research and Development Organisation, India,
focused on autonomous patrolling and path planning for a team of
car-like mobile robots. The objective was to
enable the robots to patrol designated areas while ensuring that priority
points within a cantonment were regularly visited and not left unattended.
</p>

<figure>
    <img src="multi_agents.gif"
         alt="Multiple car-like robots navigating a campus environment">
    <figcaption>
        Figure: Multi-robot autonomous patrolling and path planning in Webots
    </figcaption>
</figure>

<p align="justify">
The multi-robot patrolling algorithm was developed by a PhD student on the
IIT Bombay team. My role was to integrate the algorithm into a ROS and
Webots-based simulation framework and develop the path planning and
navigation components required to execute the generated patrol targets.
</p>

<p align="justify">
My primary contribution was vehicle-aware path generation for car-like
robots. I developed smooth feasible trajectories using techniques such as
cubic spline interpolation while accounting for the vehicle's motion
constraints. I also integrated obstacle avoidance with the path planning
pipeline, enabling the robots to navigate around obstacles while continuing
toward their assigned patrol points.
</p>
