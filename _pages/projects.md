---
title: "Projects"
layout: splash
permalink: /projects/
date: 2025-10-07
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/lab-bg.jpg
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
  actions:
    - label: "View My GitHub"
      url: "https://github.com/YourGitHubUsername"
excerpt: "Selected research and engineering projects — robotics, automation, and AI for mechanical systems."

intro:
  - excerpt: "I work at the intersection of robotics, control systems, and intelligent automation. Below are some of my featured projects."

feature_row:
  - image_path: /assets/images/dentara-thumbnail.jpg
    alt: "Dentara 1.0"
    title: "Dentara 1.0: Autonomous Dental Surgery Assistive Robotic Station"
    excerpt: "A robotic system designed to assist in dental surgeries with autonomous instrument handling, real-time computer vision, and safety-aware control."
    url: "/dentara/"
    btn_label: "Learn More"
    btn_class: "btn--primary"

  - image_path: /assets/images/energy-opt.jpg
    alt: "Energy Optimization Project"
    title: "Integrated Energy Optimization in Manufacturing"
    excerpt: "Multi-agent deep reinforcement learning system for optimal control of manufacturing microgrids integrating renewable sources and battery storage."
    url: "/energy-optimization/"
    btn_label: "Read More"
    btn_class: "btn--primary"

  - image_path: /assets/images/robot-arm.jpg
    alt: "Robotic Manipulator"
    title: "Adaptive Robotic Manipulator for Automated Assembly"
    excerpt: "Design and control of a robotic manipulator for flexible manufacturing with force feedback and adaptive motion planning."
    url: "/robotic-manipulator/"
    btn_label: "View Details"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}
{% include feature_row %}
