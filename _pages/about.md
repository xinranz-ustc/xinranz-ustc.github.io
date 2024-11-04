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

# About Me

I am currently pursuing a Ph.D. at the School of Computer Science and Technology, University of Science and Technology of China ([USTC](https://en.ustc.edu.cn/)) under the supervision of Prof. [Yanyong Zhang](http://staff.ustc.edu.cn/~yanyongz/). Prior to that, I received my B.E. degree in 2020 from School of Computer Science and Technology at Chongqing University ([CQU](https://english.cqu.edu.cn/)).



My research interest includes:
- Simultaneous Localization and Mapping (SLAM)
- Neural Radiance Fields (NeRF)
- 3D Gaussian Splatting (3DGS)


# News
+ 2024.09.09: Our paper <a href="#-rdgait">**RDGait**</a> is accepted by IMWUT!
+ 2024.02.24: Our paper <a href="#-Map">**Map++**</a> is accepted by MobiCom 2024!
+ 2024.06.30: Our paper <a href="#-mmGaussain">**MM-Gaussian**</a> is accepted by IROS 2024!
+ 2024.01.29: Our paper <a href="#-occvo">**OCC-VO**</a> is accepted by ICRA 2024!
+ 2023.07.18: Our dataset paper <a href="#-ustcfly">**USTC FLICAR**</a> is accepted by IJRR!

# Publications 

<span class='anchor' id='-rdgait'></span>
<div class='paper-box'><div class='paper-box-image'><div><div class="conference">IMWUT</div><img src='images/paper/rdgait.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- RDGait: A mmWave Based Gait User Recognition System for Complex Indoor Environments Using Single-chip Radar
-	Dequan Wang, Xinran Zhang, Kai Wang, Lingyu Wang, Xiaoran Fan, Yanyong Zhang
- Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies
 
   <a href="https://dl.acm.org/doi/abs/10.1145/3678552" style="display: inline-block; background-color: #ffffff; border-radius: 10px; padding: 3px 6px; text-decoration: none; color: black;border: 2px solid #222222;">
    link
</a>
<a href="https://github.com/DQ-WDQ/RDGait" style="display: inline-block; background-color: #ffffff; border-radius: 10px; padding: 3px 6px; text-decoration: none; color: black;border: 2px solid #222222;">
    code
</a>
<a href="/file/rdgait.txt" style="display: inline-block; background-color: #ffffff; border-radius: 10px; padding: 3px 6px; text-decoration: none; color: black;border: 2px solid #222222;">
    BibTeX
</a>
</div>
</div>

<span class='anchor' id='-MM-Gaussian'></span>
<div class='paper-box'><div class='paper-box-image'><div><div class="conference">IROS 2024</div><img src='images/paper/mmGaussian.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- MM-Gaussian: 3D Gaussian-based Multi-modal Fusion for Localization and Reconstruction in Unbounded Scenes  
-	Chenyang Wu, Yifan Duan, Xinran Zhang, Yu Sheng, Jianmin Ji, Yanyong Zhang
- 2024 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)

   <a href="https://arxiv.org/abs/2404.04026" style="display: inline-block; background-color: #ffffff; border-radius: 10px; padding: 3px 6px; text-decoration: none; color: black;border: 2px solid #222222;">
    arxiv
</a>
<a href="/file/MM-Gaussian.txt" style="display: inline-block; background-color: #ffffff; border-radius: 10px; padding: 3px 6px; text-decoration: none; color: black;border: 2px solid #222222;">
    BibTeX
</a>
</div>
</div>



<span class='anchor' id='-Map'></span>
<div class='paper-box'><div class='paper-box-image'><div><div class="conference">MobiCom 2024</div><img src='images/paper/map++.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- Map++: Towards User-Participatory Visual SLAM Systems with Efficient Map Expansion and Sharing
- Xinran Zhang, Hanqi Zhu, Yifan Duan, Wuyang Zhang, Longfei Shangguan, Yu Zhang, Jianmin Ji, Yanyong Zhang
- ACM MobiCom 2024: Proceedings of the 30th Annual International Conference on Mobile Computing and Networking
 
   <a href="https://dl.acm.org/doi/10.1145/3636534.3649386" style="display: inline-block; background-color: #ffffff; border-radius: 10px; padding: 3px 6px; text-decoration: none; color: black;border: 2px solid #222222;">
    link
</a>
<a href="/file/map++.txt" style="display: inline-block; background-color: #ffffff; border-radius: 10px; padding: 3px 6px; text-decoration: none; color: black;border: 2px solid #222222;">
    BibTeX
</a>
</div>
</div>

<span class='anchor' id='-occvo'></span>
<div class='paper-box'><div class='paper-box-image'><div><div class="conference">ICRA 2024</div><img src='images/paper/occvo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- OCC-VO: Dense Mapping via 3D Occupancy-Based Visual Odometry for Autonomous Driving
-	Heng Li, Yifan Duan, Xinran Zhang, Haiyi Liu, Jianmin Ji, Yanyong Zhang
- 2024 IEEE International Conference on Robotics and Automation (ICRA)
 
   <a href="https://arxiv.org/abs/2309.11011" style="display: inline-block; background-color: #ffffff; border-radius: 10px; padding: 3px 6px; text-decoration: none; color: black;border: 2px solid #222222;">
    arxiv
</a>
<a href="https://github.com/USTCLH/OCC-VO" style="display: inline-block; background-color: #ffffff; border-radius: 10px; padding: 3px 6px; text-decoration: none; color: black;border: 2px solid #222222;">
    code
</a>
<a href="/file/occvo.txt" style="display: inline-block; background-color: #ffffff; border-radius: 10px; padding: 3px 6px; text-decoration: none; color: black;border: 2px solid #222222;">
    BibTeX
</a>
</div>
</div>

<span class='anchor' id='-ustcfly'></span>
<div class='paper-box'><div class='paper-box-image'><div><div class="journal">IJRR</div><img src='images/paper/ustcfly.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- USTC FLICAR: A sensors fusion dataset of LiDAR-inertial-camera for heavy-duty autonomous aerial work robots
-	Ziming Wang, Yujiang Liu, Yifan Duan, Xingchen Li, Xinran Zhang, Jianmin Ji, Erbao Dong, Yanyong Zhang
- The International Journal of Robotics Research (IJRR)
 
   <a href="https://arxiv.org/abs/2304.01986" style="display: inline-block; background-color: #ffffff; border-radius: 10px; padding: 3px 6px; text-decoration: none; color: black;border: 2px solid #222222;">
    arxiv
</a>
<a href="https://ustc-flicar.github.io/" style="display: inline-block; background-color: #ffffff; border-radius: 10px; padding: 3px 6px; text-decoration: none; color: black;border: 2px solid #222222;">
    Page
</a>
<a href="/file/ustcfly.txt" style="display: inline-block; background-color: #ffffff; border-radius: 10px; padding: 3px 6px; text-decoration: none; color: black;border: 2px solid #222222;">
    BibTeX
</a>
</div>
</div>



<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# Internships
- *2022.06 - 2022.11*, Heterogenous Extreme Computing Group at Microsoft Research Asia ([MSRA](https://www.microsoft.com/en-us/research/lab/microsoft-research-asia/)).

<div style="display: flex; justify-content: center; align-items: center; height: 200px; margin: 0; padding: 0;">
    <div style="flex: 0 1 200px; margin-right: 20px;"> <!-- Adjusted flex-grow to 0 and flex-basis to 200px -->
        <img style="width: 100%; height: auto;" src="/images/ustcxhjpg/ustcblue.jpg" alt="USTC">
    </div>
    <!-- <div style="flex: 0 1 300px;"> <!-- Adjusted flex-grow to 0 and flex-basis to 300px -->
        <script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=BCzXnllK7DALNmWsuEPPoh2DRAH282QR2m3XPzLQJkg&cl=ffffff&w=a"></script>
    </div> -->
</div>