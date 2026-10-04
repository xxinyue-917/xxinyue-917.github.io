---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a Ph.D. candidate in Robotics at the University of Michigan, Ann Arbor, working with [Prof. Steven Ceron](https://robotics.umich.edu/people/faculty/steven-ceron/) on control and learning for swarm robotics and multi-robot systems. Before that, I received my B.Eng. (Hons) in Aerospace Engineering from the University of Nottingham in 2024, where I began my robotics research with [Prof. Erwin (Xin) Dong](https://www.nottingham.ac.uk/engineering/departments/m3/people/xin.dong).

# 🔥 News
- *2026.06*: One of our papers was accepted for publication in **Advanced Robotics Research**.
- *2026.06*: I presented our work at **ICRA 2026** in Vienna, Austria.
- *2026.01*: Our paper was accepted to **ICRA 2026**.
- *2025.12*: I passed my qualifying exam and advanced to Ph.D. candidacy.
- *2025.10*: Our paper was accepted for publication in **IEEE Robotics and Automation Letters (RA-L)**.
- *2025.04*: I transferred to the Ph.D. program in Robotics at the University of Michigan, working with [Prof. Steven Ceron](https://robotics.umich.edu/people/faculty/steven-ceron/).
- *2024.08*: &nbsp;🎉 I’m heading to the University of Michigan to pursue my master's degree, and I’m eager to explore more about robotics. Hoping to expand my knowledge and skills in this fascinating area!

<!-- # 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun -->

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 📝 Projects
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SLAM/Path Planning/Control</div><img src='images/exploration.gif' alt="arm" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**BotLab [[code](https://github.com/xxinyue-917/BotLab)] [[video1](https://www.youtube.com/watch?v=XKfrrkBY6D8)] [[video2](https://www.youtube.com/watch?v=Tal5JE33YDc)] [[video3](https://www.youtube.com/watch?v=lNV43ggnyME)]**

- BotLab is a course project for the UMich ROB550 - Robotic Systems Lab. This project presents an autonomous mobile robot system implemented on the differential drive MBot platform equipped with 2D LIDAR, wheel encoders, an IMU, and a camera. The system achieves precise motion control using PID feedback and a carrot-following algo- rithm, robust mapping via particle filter-based SLAM with occupancy grids, and autonomous exploration through A* path planning and frontier-based strategies. Additionally, a YOLO model was trained to detect cones and blocks for task execution. This work achieved first place in the final competition of the class.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Kinematic/CV</div><img src='images/stacking.gif' alt="arm" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**ArmLab [[code](https://github.com/xxinyue-917/ArmLab)] [[video](https://www.youtube.com/shorts/Pw4TuiCOPQg)]**

- Armlab is a course project for UMich ROB550 - Robotic Systems Lab. In this project, an RGB-D camera was used to detect the size, color, position, and height of blocks. The project also involved implementing both forward and inverse kinematics for a 5DOF robotic arm, which was then used to perform a series of tasks. This work achieved first place in the final competition.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Embedded System/Communication</div><img src='images/cyc_prop.png' alt="cyc_prop" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Cycloidal Propeller [[video](https://youtube.com/shorts/_IwL4TRK-bA)]**

- This underwater robot can move in all directions, just like McNamara wheels. This project involves achieving directional and depth-controlled movement by utilizing data from the IMU and depth sensor, along with PID control.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Algorithm</div><img src='images/drawing_robot.png' alt="drawing_robot" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Drawing Robot [[code](https://github.com//Drawing_Robot_Tic_Tac_Toe)] [[video](https://youtu.be/WPUbCplfAMw?si=HOGm8zRXLjzOUu34)]**

- The drawing robot is capable of executing Tic Tac Toe games between two players through a command-line interface. Players can select grid sizes and choose their unique patterns from a list. The robot autonomously determines the winner and visually highlights the victory by drawing a line through the matching sequence.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Design</div><img src='images/adhesion_device.JPG' alt="adhesion_device" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Swirling Adhesion [[video1](https://www.youtube.com/shorts/rjxmZVoMi4o)] [[video2](https://www.youtube.com/shorts/4uXqqEbQ6Xs)]**

- Designed and validated a non-contact swirling adhesion system for both air and underwater environments. Demonstrated that this device can generate strong suction on even rough surfaces while maintaining minimal tangential forces. This unique feature makes it highly suitable for robotic applications, enabling robots to adhere strongly to a wide range of surfaces.

</div>
</div>

# 🎖 Honors and Awards
- *2024.7*, Head of Department Award, University of Nottingham, UK

# 📖 Educations
- *2024.08 - now*, Ph.D. Robotics, University of Michigan, Ann Arbor, USA.
- *2022.09 - 2024.06*, B.Eng, Aerospace Engineering, University of Nottingham, Nottingham, UK.
- *2020.09 - 2022.06*, B.Eng, Aerospace Engineering, University of Nottingham, Ningbo, China.

<!-- # 💬 Invited Talks
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2025.05 - 2025.08*, Research Intern, [DexRobot](https://www.dex-robot.com/en), Shanghai, China.
- *2024.06 - 2024.08*, Research Intern, Marine Robotics Research Center, [Huzhou Institute of Zhejiang University](http://hzi.zju.edu.cn/), HuZhou, China.
- *2022.06 - 2022.09*, Research Intern, Ningbo Ostatus Machinery Technology Co., Ltd., Li Dak Sum Incubator, Ningbo, China.
- *2021.09 - 2022.06*, Sports Intern, [UNNC Sports Center](https://www.nottingham.edu.cn/en/sport/sport-department.aspx), Ningbo, China.

# 🧗 Hobbies
- *2022.10 - 2024.05*, Member, University of Nottingham Climbing Competition Team.
- *2021.09 - 2022.06*, Leader, University of Nottingham Ningbo China Excel Climbing Team.
- *2021.06 - 2022.06*, President, Climbing Association of Nottingham Ningbo.
- Junior Outdoor Instructor of China Mountaineering Association.