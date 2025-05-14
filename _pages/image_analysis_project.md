---
layout: splash # I've mostly used the most basic layout, single, and modified it from there but feel free to pick a different one and play around!
permalink: /image_analysis_project/ # for example, for the resources page you would put resources
hidden: true
header:
  overlay_image: /assets/path/to/image.png
title: "Image Analysis Project"
tagline: "I did this for my image analysis project!"   
author_profile: false # you can change this to true if you want this on the side again!
read_time: true # this estimates how long it will take someone to read this page
share: true # this makes this page shareable
classes: wide # formatting
sidebar:
  nav: "your_nav_heading" # I chose to use an additional sidebar to navigate different parts of this page instead of the author profile. If you use this you will have to add a new section to your navigation.yml file, or you can comment this section out.

---
<div style="display: flex; justify-content: space-between; flex-wrap: wrap;">
  <img src="/assets/Images/Screenshot%202025-05-03%20165035.png" alt="Processed cell image" style="max-width: 45%; height: auto; margin-bottom: 10px;">
  <img src="/assets/Images/Cellprofiler-icon.png" alt="CellProfiler icon" style="max-width: 45%; height: auto; margin-bottom: 10px;">
</div>

For my image analysis project, I processed images containing numerous cells to count and analyze them effectively.

I built a pipeline that:
- Smoothed cell outlines to reduce noise.
- Enhanced intensity contrast to improve segmentation.
- Used **CellProfiler** for cell counting and measurement.
