---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2026-01-05
type: landing

sections:
  # Developer Hero - Gradient background with name, role, social, and CTAs
  - block: dev-hero
    id: hero
    content:
      username: me
      greeting: "Hi, I'm"
      show_status: true
      show_scroll_indicator: true
      typewriter:
        enable: true
        prefix: "My interests include"
        strings:
        - "robotic perception, estimation and control"
        - "autonomous navigation in challenging environments"
        - "multi-modal sensor fusion"
        - "bio-inspired robotics"
        type_speed: 70
        delete_speed: 40
        pause_time: 2500
      cta_buttons:
        - text: View My Work
          url: "#projects"
          icon: arrow-down
        - text: Get In Touch
          url: "#contact"
          icon: envelope
    design:
      style: centered
      avatar_shape: circle
      animations: true
      background:
        color:
          light: "#fafafa"
          dark: "#0a0a0f"
      spacing:
        padding: ["6rem", "0", "4rem", "0"]

  # Filterable Portfolio - Alpine.js powered project filtering
  - block: portfolio
    id: projects
    content:
      title: "Featured Projects"
      subtitle: "A selection of my recent work"
      count: 3
      filters:
        folders:
          - projects
      buttons:
        - name: All
          tag: '*'
        - name: UAV Systems
          tag: UAV Systems
        - name: Autonomous Robotics
          tag: Autonomous Robotics
        - name: Perception & AI
          tag: Perception & AI
      default_button_index: 0
      # Archive link auto-shown if more projects exist than 'count' above
      # archive:
      # enable: false  # Set to false to explicitly hide
      #   text: "Browse All"  # Customize text
      #   link: "/work/"  # Custom URL
      archive:
        enable: true
        text: "Browse All"
        link: "/projects/"
    design:
      columns: 3
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]

  # Visual Tech Stack - Icons organized by category
  - block: tech-stack
    id: skills
    content:
      title: "Tech Stack"
      subtitle: "Technologies I use to build things"
      categories:
      - name: Programming
        items:
          - name: Python
            icon: devicon/python
          - name: C++
            icon: devicon/cplusplus
          - name: MATLAB
            icon: devicon/matlab

      - name: Robotics & Autonomy
        items:
          - name: ROS2
            icon: devicon/ros
          - name: Gazebo
            icon: devicon/gazebo
          - name: PX4
            icon: custom/px4
          - name: ArduPilot
            icon: custom/ardu

      - name: Perception & AI
        items:
          - name: OpenCV
            icon: devicon/opencv
          - name: PyTorch
            icon: devicon/pytorch

      - name: Embedded Systems
        items:
          - name: NVIDIA Jetson
            icon: custom/nvidia
          - name: STM32
            icon: custom/stm32
          - name: Raspberry Pi
            icon: devicon/raspberrypi

    design:
      style: grid
      show_levels: false
      background:
        color:
          light: "#f5f5f5"
          dark: "#08080c"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]

  # Experience Timeline
  - block: resume-experience
    id: experience
    content:
      title: Experience
      date_format: Jan 2006
      items:

        - title: Project Manager
          company: Drone Center, IIT Bombay
          company_url: ''
          company_logo: ''
          location: Mumbai, India
          date_start: '2025-09-01'
          date_end: ''
          description: |2-
            * Researching and developing GPS-denied terrain-following navigation algorithms using LiDAR, monocular vision, and IMU with VPS and VIO.
            * Developing multi-modal sensor systems for UAV obstacle avoidance and high-speed navigation, and evaluating state-of-the-art object detection models for bunker detection.

        - title: Principal Engineer – State Estimation and Control
          company: TIH Foundation for IoT & IoE, IIT Bombay
          company_url: ''
          company_logo: ''
          location: Mumbai, India
          date_start: '2024-04-01'
          date_end: '2025-09-01'
          description: |2-
            * Led development and field validation of lightweight sense-and-avoid systems and multimodal sensing systems for agricultural UAVs.
            * Developed UAV and ground-robot localization pipelines using VIO, ROS, PX4, and NVIDIA Jetson.

        - title: Senior Engineer – State Estimation and Control
          company: TIH Foundation for IoT & IoE, IIT Bombay
          company_url: ''
          company_logo: ''
          location: Mumbai, India
          date_start: '2022-06-01'
          date_end: '2024-03-31'
          description: |2-
            * Developed UAV localization, navigation, and perception systems using VIO, deep learning, and aerial multispectral sensing.
            * Developed autonomous ground-robot odometry and localization pipelines and validated robotic systems through simulation and field testing.

        - title: Senior Research Fellow
          company: Autonomous Robots and Multi-Robot Systems (ARMS) Lab, IIT Bombay
          company_url: 'https://www.sc.iitb.ac.in/robotics/'
          company_logo: ''
          location: Mumbai, India
          date_start: '2019-03-01'
          date_end: '2021-08-01'
          description: |2-
            * Developed trajectory generation, tracking, and static/dynamic obstacle avoidance algorithms for autonomous multi-agent robotic systems.
            * Integrated and validated robotic algorithms using ROS and Webots for autonomous patrolling applications.

        - title: Software Developer
          company: AISIGHT Video Analytics Pvt. Ltd.
          company_url: ''
          company_logo: ''
          location: Mumbai, India
          date_start: '2018-07-01'
          date_end: '2019-01-01'
          description: |2-
            * Developed computer vision and deep learning pipelines for surveillance, anomaly detection, and human tracking.
            * Implemented video analytics systems using OpenCV, PyTorch, TensorFlow, C++, and Python.

        - title: Drone and Robotics Engineer
          company: Dhristi Works
          company_url: 'http://www.drishti.works/'
          company_logo: ''
          location: Mumbai, India
          date_start: '2017-12-01'
          date_end: '2018-06-01'
          description: |2-
            * Developed motion planning, object detection, point-cloud processing, and grasping pipelines for robotic manipulators.
            * Worked with ROS, Gazebo, and MoveIt for autonomous manipulation applications.

        - title: Research Assistant
          company: Singapore Institute of Neurotechnology, National University of Singapore
          company_url: 'https://neuroeng.org/'
          company_logo: ''
          location: Singapore
          date_start: '2016-03-01'
          date_end: '2017-03-01'
          description: |2-
            * Developed robotic slip-control and haptic feedback systems for robotic manipulators and prosthetic interfaces.
            * Worked on robotic manipulation and motion planning using UR10 systems, MATLAB, Simulink, C++, and Python.

        - title: Project Assistant
          company: Multimodal Perception Laboratory, IIIT Bangalore
          company_url: 'http://mpl.iiitb.ac.in/'
          company_logo: ''
          location: Bangalore, India
          date_start: '2015-08-01'
          date_end: '2015-12-01'
          description: |2-
            * Developed and evaluated image segmentation algorithms for jewelry segmentation, including a modified GrabCut approach using OpenCV and C++.

        - title: Assistant Professor
          company: Haryana College of Technology and Management
          company_url: ''
          company_logo: ''
          location: Haryana, India
          date_start: '2014-08-01'
          date_end: '2015-04-01'
          description: |2-
            * Taught Digital Signal Processing, Microprocessors and Interfacing, and Digital Communication, including laboratory courses.

        - title: Project Manager – Embedded Software Engineer
          company: Infinite Biomedical Technologies
          company_url: 'https://www.i-biomed.com/'
          company_logo: ''
          location: Baltimore, USA
          date_start: '2012-09-01'
          date_end: '2013-04-01'
          description: |2-
            * Developed EMG-based pattern recognition and control algorithms for a prosthetic arm, enabling recognition of multiple hand gestures.
            * Implemented signal classification pipelines using C++ and MATLAB.

    design:
      columns: '1'
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
  # Recent Blog Posts
  #- block: collection
  #  id: blog
  #  content:
  #    title: Recent Posts
  #    subtitle: 'Thoughts on web development, tech, and more'
  #    text: ''
  #    filters:
  #      folders:
  #        - blog
  #      exclude_featured: false
  #    count: 3
  #    order: desc
  #  design:
  #    view: card
  #    columns: 3
  #    background:
  #      color:
  #        light: "#f5f5f5"
  #        dark: "#08080c"
  #    spacing:
  #      padding: ["4rem", "0", "4rem", "0"]

  # Contact Section
  - block: contact-info
    id: contact
    content:
      title: Get In Touch
      subtitle: "Let's build something amazing together"
      text: |-
        Open to technical collaborations, research partnerships, and prospective opportunities.
        Feel free to connect or send a message.
      email: dimple.bhuta@gmail.com
      autolink: true
    design:
      columns: '1'
      background:
        color:
          light: "#f5f5f5"
          dark: "#08080c"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]

  # CTA Card
  - block: cta-card
    id: resume
    content:
      title: "Open to Opportunities"
      text: |-
        Currently open to senior engineering roles, research positions, and high impact projects in robotics and autonomy.
        Let’s connect to discuss potential roles or research partnerships.
      button:
        text: 'Download Resume'
        url: uploads/resume.pdf
        new_tab: true
    design:
      card:
        # Light mode: soft pastel theme gradient | Dark mode: rich deep gradient
        css_class: 'bg-gradient-to-br from-primary-200 via-primary-100 to-secondary-200 dark:from-primary-600 dark:via-primary-700 dark:to-secondary-700'
        text_color: dark
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding: ["4rem", "0", "6rem", "0"]
---
