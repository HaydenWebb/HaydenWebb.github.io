---
layout: page
title: Automated Biosensor Screener
description: automated device for fabricating electrodes
img: assets/img/ABS_Promotional.png
importance: 1
category: others
---

### Description

The Sempionatto Research Group develops wearable biosensors that collect and analyze sweat, blood, and other biofluids to monitor the wearer’s health. These wearable sensors must be flexible and thus are made by screen printing the electrode design with a conductive ink. Since existing screen-printing machines are bulky and expensive, the electrodes used in these sensors are often screen-printed by hand, which is time-consuming, inconsistent, and wastes a large amount of ink. Devloped device is low-cost, time-efficient, and has a 95% yield in creating electrodes for biosensors.

<div style="display: flex; justify-content: space-between; gap: 10px;">
    <img src="/assets/img/ABS_Differential.png" alt="ABS Differential" title="ABS Differential" style="max-width: 100%; height: auto; flex: 1;">
    <img src="/assets/img/ABS_UI.png" alt="ABS UI Example" title="ABS UI Example" style="max-width: 100%; height: auto; flex: 1;">
    <img src="/assets/img/ABS_Motion_Plan.png" alt="ABS Motion Plan" title="ABS Motion Plan" style="max-width: 100%; height: auto; flex: 1;">
</div>


### Personal Contribution

Independently developed the overall design of the gantry (including X & Y movement systems) as well as the squeegee subsystem. This includes the pictured lock differential, machined top plate, and electronic undercarriage. Personally lead and completed the physical construction of the device including the waterjet cutting, 3D printing, and laser-cutting utilized in the device's fabrication. <br>

Designed a primitive weighted motion planner for ink and screening toolpaths, generating task-space coordinates with motor control flags in G-code format for electronics bus. Wrote parroting and file parsing algorithms for sending and receiving commands & flags from the UI and system's microprocessor. Additionally developed closed-loop velocity and positon control for use in executing gcode, homing, and jogging device via user commands. <br>

Developed a custom UI for preprocessing electrode vector files, modeled after common 3D printing slicers to streamline tool path generation, repeated electrode Cricut file,  and parameter tuning. See poster below for examples of UI <br>

Oversaw team deadlines and communication with sponsors and collaborators, ensuring proper communication on work between  the client and development team throughout the project
Performed several technical design reviews on mechanical subsections to ensure feasibility and design optimization in terms of modularity, cost, and ease of construction <br>

### Poster

<img title="ABS Poster" alt="Alt text" src="/assets/img/ABS_Poster.png" width="864" height = "648">

