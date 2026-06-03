---
layout: page
title: Brain-Controlled Wheelchair
description: BCI-Controlled Wheelchair utilizing OpenBCI EEG hardware and MindAffect stimulus software
img: assets/img/bciwheelchair1.jpg
importance: 1
category: work
---

**Project Role:** Lead Developer & Systems Integrator  
**Timeline:** January 2026 – June 2026  
**Status:** Functional Prototype / Data Validation Phase

## Overview
This project aimed to improve mobility for individuals with motor impairments by developing a brain-computer interface (BCI) capable of translating neural activity into mechanical control for a motorized wheelchair.

## Technical Stack
* **Hardware:** OpenBCI Ganglion Board and Electrode Headset
* **Software:** Python (Signal processing, Logic controller), MindAffect Software, Arduino IDE
* **Systems:** Hardware-in-the-loop (HITL) integration, UART/Serial communication

## Key Engineering Challenges
1. **Signal Noise Filtration:** Developing robust Python scripts to isolate EEG data from environmental artifacts.
2. **Latency Reduction:** Optimizing the processing pipeline to ensure real-time actuation, minimizing the delay between neural intent and wheelchair movement.
3. **Human-Machine Safety:** Implementing an emergency override protocol within the control loop to ensure user safety during testing.

## Key Achievements
* Successfully demonstrated translation of BCI inputs into directed wheelchair movement commands
* Validated viability of low-cost, open-source BCI hardware in medical applications
* Integrated 4 ultrasonic sensors for real-time obstacle detection and safety stops
* Designed and prototyped a rack-and-pinion joystick actuation mechanism using SOLIDWORKS

## Images (coming soon)
1. Full wheelchair
2. Joystick device  
3. MindAffect stimulus interface
4. Electrical schematics

## Demonstrations
<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    <video width="100%" autoplay loop muted playsinline class="img-fluid rounded z-depth-1">
      <source src="{{ '/assets/video/bci-stop.mov' | relative_url }}" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
</div>
<div class="caption">
  BCI-controlled wheelchair prototype performing obstacle avoidance (when detecting my hand) during live EEG testing.
</div>
---
[View the Source Code and Documentation on GitHub](https://github.com/elinaxiv/mindcontrolledwheelchair)
