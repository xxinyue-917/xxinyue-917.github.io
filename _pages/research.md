---
permalink: /research/
title: "Research"
excerpt: "Research highlights and publications in robotics."
author_profile: true
---

# 🔬 Research Highlights

<div class="paper-box research-highlight" id="dexcanvas">
  <div class="paper-box-image">
    <div>
      <img src="{{ '/images/dexcanvas-pipeline.gif' | relative_url }}" alt="DexCanvas pipeline from human motion capture to MANO hand reconstruction and physics simulation" width="560" height="425">
    </div>
  </div>
  <div class="paper-box-text" markdown="1">

<h3 id="dexcanvas-title">DexCanvas <a href="https://arxiv.org/abs/2510.15786">[Paper]</a> <a href="https://github.com/dexrobot/dexcanvas">[Code]</a> <a href="https://huggingface.co/datasets/Dex-GEM/DexCanvas">[Dataset]</a></h3>

DexCanvas is a hybrid dataset for learning dexterous manipulation from human demonstrations. Our pipeline converts motion-capture recordings into MANO hand trajectories and uses reinforcement learning to reproduce hand–object interactions in physics simulation, recovering contact forces that are difficult to measure directly. By combining human motion with physics-based contact annotations, DexCanvas provides data for learning contact-rich manipulation skills.

  </div>
</div>

<div class="paper-box research-highlight" id="swarmalators">
  <div class="paper-box-image">
    <div>
      <img src="{{ '/images/swarmalators-navigation.gif' | relative_url }}" alt="Simulated unicycle swarmalators navigating through obstacles using local control" width="560" height="560">
    </div>
  </div>
  <div class="paper-box-text" markdown="1">

<h3 id="swarmalators-title">Navigation of Robotic Swarmalators <a href="https://doi.org/10.1109/LRA.2025.3640404">[Paper]</a> <a href="{{ '/videos/swarmalators-navigation.mp4' | relative_url }}">[Video]</a></h3>

We adapt the swarmalator model to robots with omnidirectional, unicycle, and bicycle dynamics, examining how motion constraints reshape collective behavior. Combining swarmalator planning with control barrier functions enables global and per-agent control for navigation through cluttered environments and object transport around obstacles.

  </div>
</div>

<div class="paper-box research-highlight" id="magflow">
  <div class="paper-box-image">
    <div>
      <img src="{{ '/images/magflow-demo.gif' | relative_url }}" alt="MagFlow magnetic millirobot collectives reconfiguring between shapes and separating into eight color groups" width="420" height="364">
    </div>
  </div>
  <div class="paper-box-text" markdown="1">

<h3 id="magflow-title">MagFlow <span class="research-paper-status">[Paper: Under review]</span></h3>

MagFlow controls collectives of passive magnetic millirobots through a shared electromagnetic field. Using camera-based density feedback, optimal transport guides the swarm toward target shapes, while a constrained control allocator converts the desired motion into feasible electromagnet commands. The system enables reset-free shape reconfiguration and separation of multiple groups. These capabilities are verified in both simulation and hardware experiments.

  </div>
</div>

# 📄 Publications

<p class="publication-note"><sup>&#42;</sup> Equal contribution.</p>

## 2026

<div class="publication-entry" markdown="1">

### Nonreciprocal Swarmalators With Reconfigurable and Controllable Formations for Robot Collectives

Kush Patel<sup>&#42;</sup>, **Xinyue Xu**<sup>&#42;</sup>, Wei Xiao, and Steven Ceron.  
*Advanced Robotics Research*, e70161, 2026.  
[Paper](https://doi.org/10.1002/adrr.70161)

</div>

<div class="publication-entry" markdown="1">

### 3D Robotic Swarmalators That Reconfigure, Navigate, and Avoid Obstacles

Zehui Xu<sup>&#42;</sup>, **Xinyue Xu**<sup>&#42;</sup>, and Steven Ceron.  
*IEEE International Conference on Robotics and Automation (ICRA)*, 2026.

</div>

<div class="publication-entry" markdown="1">

### Navigation of Robotic Swarmalators With Dynamics and Constraints

**Xinyue Xu**, Wei Xiao, and Steven Ceron.  
*IEEE Robotics and Automation Letters (RA-L)*, 11(2), 1066–1073, 2026.  
[Paper](https://doi.org/10.1109/LRA.2025.3640404)

</div>

## 2025

<div class="publication-entry" markdown="1">

### DexCanvas: Bridging Human Demonstrations and Robot Learning for Dexterous Manipulation

**Xinyue Xu**, Jieqiang Sun, Jing (Daisy) Dai, Siyuan Chen, Lanjie Ma, Ke Sun, Bin Zhao, Jianbo Yuan, Sheng Yi, Haohua Zhu, and Yiwen Lu.  
*arXiv preprint*, arXiv:2510.15786, 2025.  
[Paper](https://arxiv.org/abs/2510.15786) · [Code](https://github.com/dexrobot/dexcanvas) · [Dataset](https://huggingface.co/datasets/Dex-GEM/DexCanvas)

</div>
