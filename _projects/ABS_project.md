---
layout: page
title: Automated Biosensor Screener
description: automated device for fabricating biosensors
img: assets/img/ABS_Promotional.png
importance: 1
category: others
---

<img title="differential" alt="differential" src="/assets/img/ABS_Differential.png" width="480" height = "360">

### Description

The Sempionatto Research Group develops wearable biosensors that collect and analyze sweat, blood, and other biofluids to monitor the wearer’s health. These wearable sensors must be flexible and thus are made by screen printing the electrode design with a conductive ink. Since existing screen-printing machines are bulky and expensive, the electrodes used in these sensors are often screen-printed by hand, which is time-consuming, inconsistent, and wastes a large amount of ink. The goal of this project is to build a desktop-sized printer that automates this process while minimizing wasted ink. The mid-semester checkpoint that summarizes the work can be found below.

<div style="display: flex; justify-content: space-between;">
    <img title="ABS Repeated Dxf" alt="ABS Repeated DXF" src="/assets/img/ABS_Repeated_DXF.png" style="width: 45%; margin-right: 5px;">
    <img title="ABS Motion Plan" alt="ABS Motion Plan" src="/assets/img/ABS_Motion_Plan.png" style="width: 45%; margin-right: 5px;">
</div> <br>

### Personal Contribution

Independently developed the overall design of the gantry including the X & Y movement systems. This includes the pictured lock differential, machined top plate, and electronic undercarriage. Personally lead and completed the physical construction of the device including the waterjet cutting, 3D printing, and laser-cutting utilized in the device's fabrication. <br>

Independently developed the overall file parser and motion planner utilized in the device's control scheme as shown. Developed code takes in user's vector file of biosensor and outputs two main files. The first is a DXF of repeated sensors according to user input (number, rotation angle, offset, etc.) for use in a Cricket or other cutting machine. The second is a motion plan of cardinal points for both the ink deposition (shown in green) and the squeegee motion (shown in orange). The squeegee motion is found through creating a convex hull (shown in blue) around the aforementioned repeated sensor DXF and solving to cover the area with the toolhead while limiting distance travelled and not hitting obstables (shown in red). The ink motion is found through using the sensors bounding box edges as edges to travel and solving from there while still limiting distance.

Additionaly lead team meetings, maintained team budget, and upheld team and university deadlines as team project manager. <br>

<embed src="/assets/pdf/ABS_Checkpoint.pdf" width="816px" height="1056px" />
