---
title: "Visual-Inertial Localization for UAVs in Agricultural Environments"
weight: 3
date: 2023-04-03
show_date: false
show_date_updated: false
reading_time: false
share: false

summary: "Evaluation of a feedback-based visual-inertial system across structured and unstructured simulated environments."

tags:
  - UAV Systems

tech_stack:
  - Python
  - ROS
  - Gazebo
  - Visual-Inertial Odometry
  - UAV Localization
  - Sensor Fusion

links:
  - type: video
    url: "https://youtu.be/6mZ6PYJoz3o"
    label: "YouTube"

featured: true
---

<style>
@media (max-width: 768px) {
  .environment-grid,
  .localization-pair {
    grid-template-columns: 1fr !important;
  }
}
</style>

<p align="justify">
At TIH, IIT Bombay, I worked on visual-inertial localization for UAVs
in GNSS-denied agricultural environments. I evaluated the
feedback-based visual-inertial system (FVIS) described in the
<a href="https://ieeexplore.ieee.org/document/10155195"
   target="_blank"
   rel="noopener">
published work
</a>
for UAV pose estimation using visual and IMU measurements.
</p>

<p align="justify">
I developed a Gazebo simulation using an Iris quadcopter equipped with
a downward-facing Intel RealSense depth camera. The system was evaluated
across structured and unstructured agricultural environments at flight
altitudes of 3.5 m, 10 m, and 20 m.
</p>

<figure>
    <img src="9_flvis.gif"
         alt="Visual-inertial localization of an Iris quadcopter"
         style="width: 100%; height: auto; display: block;">
    <figcaption>
        Figure 1: Visual-inertial localization of an Iris quadcopter
        in a simulated agricultural environment
    </figcaption>
</figure>

<h3>Simulation Environments</h3>

<p align="justify">
The system was evaluated in three environments with different levels
of visual structure.
</p>

<div class="environment-grid" style="
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 24px;
  align-items: start;
  margin: 30px 0 40px 0;
">

  <figure style="margin: 0; text-align: center;">
    <img src="mh_top.png"
         alt="Manhattan World simulation environment"
         style="width: 100%; height: auto; display: block;">
    <figcaption style="margin-top: 10px;">
      <b>Manhattan World</b><br>
      Structured environment with rich and diverse visual features
      <br>
      <a href="https://youtu.be/9dqaCNd7JSQ"
         target="_blank"
         rel="noopener">
        Simulation Video
      </a>
    </figcaption>
  </figure>

  <figure style="margin: 0; text-align: center;">
    <img src="fg_top.png"
         alt="Farm Grid World simulation environment"
         style="width: 100%; height: auto; display: block;">
    <figcaption style="margin-top: 10px;">
      <b>Farm Grid World</b><br>
      Structured agricultural environment with regular feature arrangement
      <br>
      <a href="https://youtu.be/7Z7jOObbWBc"
         target="_blank"
         rel="noopener">
        Simulation Video
      </a>
    </figcaption>
  </figure>

  <figure style="margin: 0; text-align: center;">
    <img src="farm_rand_top.png"
         alt="Farm Random Arrangement simulation environment"
         style="width: 100%; height: auto; display: block;">
    <figcaption style="margin-top: 10px;">
      <b>Farm Random Arrangement</b><br>
      Unstructured environment with randomly distributed features
      <br>
      <a href="https://youtu.be/cHfQndy20NI"
         target="_blank"
         rel="noopener">
        Simulation Video
      </a>
    </figcaption>
  </figure>

</div>

<p align="justify">
For each environment, the estimated position and velocity were compared
with simulation ground truth at flight altitudes of 3.5 m, 10 m, and 20 m.
</p>

<h3>Localization Results</h3>

<h4>Manhattan World</h4>

<div class="localization-pair" style="
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 24px;
  align-items: start;
  margin: 20px 0 45px 0;
">

  <figure style="margin: 0; text-align: center;">
    <img src="mh_pose.png"
         alt="Manhattan World position estimates"
         style="width: 100%; height: auto; display: block;">
    <figcaption style="margin-top: 10px;">
      <b>Position</b><br>
      Estimated and ground-truth position at 3.5 m, 10 m, and 20 m
    </figcaption>
  </figure>

  <figure style="margin: 0; text-align: center;">
    <img src="mh_vel_plot.png"
         alt="Manhattan World velocity estimates"
         style="width: 100%; height: auto; display: block;">
    <figcaption style="margin-top: 10px;">
      <b>Velocity</b><br>
      Estimated and ground-truth velocity at 3.5 m, 10 m, and 20 m
    </figcaption>
  </figure>

</div>

<h4>Farm Grid World</h4>

<div class="localization-pair" style="
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 24px;
  align-items: start;
  margin: 20px 0 45px 0;
">

  <figure style="margin: 0; text-align: center;">
    <img src="fg_pose.png"
         alt="Farm Grid World position estimates"
         style="width: 100%; height: auto; display: block;">
    <figcaption style="margin-top: 10px;">
      <b>Position</b><br>
      Estimated and ground-truth position at 3.5 m, 10 m, and 20 m
    </figcaption>
  </figure>

  <figure style="margin: 0; text-align: center;">
    <img src="fg_vel_plot.png"
         alt="Farm Grid World velocity estimates"
         style="width: 100%; height: auto; display: block;">
    <figcaption style="margin-top: 10px;">
      <b>Velocity</b><br>
      Estimated and ground-truth velocity at 3.5 m, 10 m, and 20 m
    </figcaption>
  </figure>

</div>

<h4>Farm Random Arrangement</h4>

<div class="localization-pair" style="
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 24px;
  align-items: start;
  margin: 20px 0 45px 0;
">

  <figure style="margin: 0; text-align: center;">
    <img src="fr_pose.png"
         alt="Farm Random Arrangement position estimates"
         style="width: 100%; height: auto; display: block;">
    <figcaption style="margin-top: 10px;">
      <b>Position</b><br>
      Estimated and ground-truth position at 3.5 m, 10 m, and 20 m
    </figcaption>
  </figure>

  <figure style="margin: 0; text-align: center;">
    <img src="fr_vel_plot.png"
         alt="Farm Random Arrangement velocity estimates"
         style="width: 100%; height: auto; display: block;">
    <figcaption style="margin-top: 10px;">
      <b>Velocity</b><br>
      Estimated and ground-truth velocity at 3.5 m, 10 m, and 20 m
    </figcaption>
  </figure>

</div>
