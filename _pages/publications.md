---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Technical Reports

<div class="archive__item">

  <h3 class="archive__item-title">
    Smart Obstacle &amp; Object Detection Glasses — Technical Report
    <span class="page__meta">(2026)</span>
  </h3>

  <p class="page__meta">
    <strong>Author:</strong> Omar Hussein Nady &nbsp;|&nbsp;
    <strong>Type:</strong> Technical Report &nbsp;|&nbsp;
    <strong>Domain:</strong> Assistive Wearables • Embedded AI • Computer Vision
  </p>

  <p>
    <strong>Summary:</strong>
    A practical assistive wearable system designed to support blind users in daily mobility and independent object/food evaluation.
    The solution combines 3D-printed smart glasses with a Raspberry Pi camera and distance sensors (ultrasonic + IR) to perceive the surroundings
    and estimate obstacle proximity in real time. Processing is performed on a Raspberry Pi 4 (8GB) embedded within a lightweight gauntlet.
    Three YOLOv8 models are used for pathway detection, obstacle detection, and fruit identification, with real-time audio feedback delivered via an onboard speaker.
    The design prioritizes low cost, energy efficiency, and real-world usability.
  </p>

  <p><strong>Highlights:</strong></p>
  <ul>
    <li>3D-printed wearable form factor with real-time sensing (ultrasonic + IR) and vision.</li>
    <li>On-device inference on Raspberry Pi 4 with YOLOv8 for pathways, obstacles, and fruit identification.</li>
    <li>Audio guidance for navigation and object/food awareness in real-world usage scenarios.</li>
    <li>Designed for practicality: low cost, energy efficient, and lightweight deployment-oriented build.</li>
  </ul>

  <p>
    <strong>Keywords:</strong>
    Assistive Wearables, Embedded Systems, Computer Vision, Object Detection, OpenCV, YOLOv8, Raspberry Pi, Real-Time Systems, GPS
  </p>

  <p>
    <a class="btn btn--primary"
       href="{{ '/files/Smart_Glasses_Technical_Report.pdf' | relative_url }}"
       target="_blank" rel="noopener">
       Download PDF
    </a>
  </p>

  <details>
    <summary><strong>Read Abstract</strong></summary>
    <p style="margin-top: 0.75rem;">
      The Smart obstacle &amp; object detection glasses project aims to help blind people in their daily lives by supporting both safe navigation
      and independent evaluation of food, in combination with cane or service pets. The system uses 3D-printed smart glasses with a Raspberry Pi camera,
      ultrasonic and IR sensors to capture the surrounding environment and estimate how dangerously close obstacles are to the user, while a gauntlet containing
      a Raspberry Pi 4B (8GB) performs all processing. Three YOLOv8n models are employed: one for pathways, one for obstacles, and one for fruit identification.
      A speaker module mounted on the glasses provides real-time audio feedback, giving simple guidance commands for navigation or clear messages about fruit safety,
      with the overall goal of offering a low-cost, energy-efficient, and sustainable smart glasses solution for blind users.
    </p>
  </details>

  <figure class="half" style="margin-top: 1.25rem;">
    <a href="{{ '/images/imagessmart-glassesxxx.jpg' | relative_url }}">
      <img src="{{ '/images/imagessmart-glassesxxx.jpg' | relative_url }}"
           alt="Smart Glasses — Prototype hardware">
    </a>

    <a href="{{ '/images/imagessmart-glassesyyy.png' | relative_url }}">
      <img src="{{ '/images/imagessmart-glassesyyy.png' | relative_url }}"
           alt="Smart Glasses — Results figure">
    </a>

    <figcaption>Project snapshots: prototype hardware and results/analysis figure.</figcaption>
  </figure>

</div>
