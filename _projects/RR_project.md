---
layout: page
title: Roller Ring
description: modular wearable in-hand manipulator
img: assets/img/roller_ring_promotional.png
importance: 2
category: research
related_publications: true
---

<div style="text-align: center;">
  <video width="640" height="480" controls>
    <source src="/assets/video/roller_ring_video.mp4" type="video/mp4">
  </video>
</div>

<div style="text-align: center;">
  <span style="color: red; font-weight: normal;">Award: 3rd Place SMRDC Undergraduate Division</span>
</div> 
<div style="text-align: center;">
  <span style="color: red; font-weight: normal;">Published: 2025 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2025)</span>
</div>

### Abstract

In-hand manipulation is a crucial ability for reorienting and repositioning objects within grasps. The main challenges in this are not only the complexity of the computational models, but also the risks of grasp instability caused by active finger motions, such as rolling, sliding, breaking, and remaking contacts. This paper presents the development of the Roller Ring (RR), a modular robotic attachment with active surfaces that is wearable by both robot and human hands to manipulate without lifting a finger. By installing the angled RRs on hands, such that their spatial motions are not colinear, we derive a general differential motion model for manipulating objects. Our motion model shows that complete in-hand manipulation skill sets can be provided by as few as only 2 RRs through non-holonomic object motions, while more RRs can enable enhanced manipulation dexterity with fewer motion constraints. Through extensive experiments, we test the RRs on both a robot hand and a human hand to evaluate their manipulation capabilities. We show that the RRs can be employed to manipulate arbitrary object shapes to provide dexterous in-hand manipulation. The paper's preprint can be found [here](https://arxiv.org/abs/2403.13132) and the citation below.


### Personal Contribution

Developed the mechanical design of the Roller Ring as well as the manipulation algorithms to create a device capable of optimally manipulating objects in 3D space when affixed to both robot & human grasping systems. Code base & robot hand for the test environment came from the [Yale OpenHand Project](https://www.eng.yale.edu/grablab/openhand/) and was further modified to accommodate the Roller Ring. <br>

### Poster

<img title="Roller Ring Poster" alt="Alt text" src="/assets/img/Roller_Ring_Poster_[site].png" width="864" height = "648">

### Citation

```bibtex
@misc{2403.13132,
    Author = {Hayden Webb and Podshara Chanrungmaneekul and Shenli Yuan and Kaiyu Hang},
    Title = {Wearable Roller Rings to Augment In-Hand Manipulation through Active Surfaces},
    Year = {2024},
    Eprint = {arXiv:2403.13132},
}
```