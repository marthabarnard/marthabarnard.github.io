---
layout: profiles
permalink: /Research/
title: Research
description: My current research focuses on developing causal inference and statistical and machine learning methods for large observational studies, generally, and mobile health data (e.g., accelerometer, heart rate, and GPS tracking data, etc.), specifically. I am especially interested in constructing methods that are both rigorous and flexible such that they are accessible to healthcare professionals and can be tailored to various research questions of interest. More specifics about the data and problems that motivate my current work can be found below.
nav: true
nav_order: 2

profiles:
  # if you want to include more than one profile, just replicate the following block
  # and create one content file for each profile inside _pages/
  - align: right
    image: week_clust.jpeg
    content: mobile_health.md
    image_circular: false # crops the image to make it circular
    more_info: >
      Monday-Friday human activity clusters identified by
      <a href="https://www.tandfonline.com/doi/full/10.1080/01621459.2025.2506196">Adjacency Matrix Decomposition Clustering</a>
  - align: left
    image: rhc_contours.png
    content: overlap.md
    image_circular: false # crops the image to make it circular
    more_info: >
      Characterizating the set of potential estimands to
      <a href="https://arxiv.org/abs/2410.12093">identify an approximately optimal estimand</a>
      under positivity violations
---
