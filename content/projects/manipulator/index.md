---
title: "Programming Robotic Manipulator for Pick-and-Place Tasks"
weight: 10
date: 2023-04-03
show_date: false
show_date_updated: false
reading_time: false
share: false

summary: "Robotic manipulator control and grasping for autonomous beach cleaning."

tags:
  - Autonomous Robotics

tech_stack:
  - Python
  - ROS
  - Motion planning
  - MoveIt
  - GraspIt!

links:
  - type: video
    url: "https://youtu.be/RO7EYPQY84E"
    label: "YouTube"

featured: true
---

<p align="justify">
At Dhristi Works, I worked on the development of robotic systems for
automated beach cleaning. My focus was on developing algorithms for a
robotic manipulator to perform pick-and-place tasks, with the intended
application of identifying and collecting garbage and placing it into a
bag or bin mounted on a mobile rover.
</p>

<p align="justify">
I used ROS to interface a 5-DOF robotic arm with the Gazebo simulator,
enabling the robot to be controlled through ROS in both simulated and
real environments. This provided a common software interface for
developing and testing manipulation algorithms before deployment on the
physical robot.
</p>

<figure>
    <img src="pickplace.gif"
         alt="ROS-controlled robotic manipulator">
    <figcaption>
        Figure 1: Robotic manipulator controlled through ROS in simulated and real environments
    </figcaption>
</figure>

<div style="
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 40px;
  align-items: center;
  margin: 40px 0;
">

  <!-- Description -->
  <div>
    <p align="justify">
      For object grasping, I compared and analyzed several available grasping
      techniques and interfaced the selected approach with the simulated robot.
      The system was evaluated on household objects in a simulated environment
      as a step toward autonomous garbage collection.
    </p>
  </div>

  <!-- Image -->
  <figure style="
    margin: 0;
    text-align: center;
  ">
    <img src="reach.gif"
         loading="lazy"
         alt="Robotic arm grasping household objects"
         style="
           display: block;
           width: 100%;
           max-width: 550px;
           height: auto;
           margin: 0 auto;
         ">
    <figcaption style="
      margin-top: 10px;
      text-align: center;
    ">
      Figure 2: Robotic arm grasping household objects in simulation
    </figcaption>
  </figure>

</div>
