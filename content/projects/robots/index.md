---
title: "Development of Motion Planning Algorithms for Robots"
weight: 11
date: 2023-04-03
show_date: false
show_date_updated: false
reading_time: false
share: false

summary: "Motion planning and control for robotic manipulation and hand control."

tags:
  - Autonomous Robotics

tech_stack:
  - C++
  - Motion Planning
  - Trajectory Generation
  - Robotic Manipulation

links:
  - type: video
    url: "https://youtu.be/OGpZnJe8gno"
    label: "YouTube"

featured: true
---

<div style="
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 50px 40px;
  align-items: start;
  margin: 30px 0 50px 0;
">

  <!-- Bread cutting -->
  <figure style="
    grid-column: 1 / -1;
    margin: 0;
    text-align: center;
  ">
    <img src="a_bread.gif"
         loading="lazy"
         alt="Robot performing bread cutting task"
         style="
           display: block;
           width: 60%;
           max-width: 700px;
           height: auto;
           margin: 0 auto;
         ">
    <figcaption style="
      margin-top: 12px;
      text-align: center;
    ">
      (a) Bread cutting task
    </figcaption>
  </figure>


  <!-- Wine bottle -->
  <figure style="
    margin: 0;
    text-align: center;
  ">
    <img src="b_wine.gif"
         loading="lazy"
         alt="Robot opening a wine bottle corkscrew"
         style="
           display: block;
           width: 100%;
           max-width: 600px;
           height: auto;
           margin: 0 auto;
         ">
    <figcaption style="
      margin-top: 12px;
      text-align: center;
    ">
      (b) Corkscrew unlocking task
    </figcaption>
  </figure>


  <!-- Robotic hand -->
  <figure style="
    margin: 0;
    text-align: center;
  ">
    <img src="c_hand.gif"
         loading="lazy"
         alt="Programmatic control of a robotic hand"
         style="
           display: block;
           width: 100%;
           max-width: 600px;
           height: auto;
           margin: 0 auto;
         ">
    <figcaption style="
      margin-top: 12px;
      text-align: center;
    ">
      (c) Programmatic control of a robotic hand
    </figcaption>
  </figure>

</div>

<div style="clear: both;"></div>

<p align="justify">
At the Singapore Institute of Neurotechnology (SINAPSE), National University
of Singapore, I worked in collaboration with the Office of Naval Research
Singapore on robotic manipulation for everyday tasks.
</p>

<p align="justify">
My work focused on motion planning and control for robotic manipulation.
For the UR10 robot, I designed and implemented zig-zag and spiral motion
trajectories for tasks including bread cutting and corkscrew opening. I also
developed a programmatic interface for controlling the individual digits of
an i-LIMB robotic hand.
</p>
