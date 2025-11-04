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

<!-- Include Google Scholar stats script -->
{% include fetch_google_scholar_stats.html %}

<span class='anchor' id='about-me'></span>

Hi there! I'm **Min Hua (华敏)**, a **Ph.D. candidate in Engineering** at the **University of Birmingham**, where I’m fortunate to be advised by **Prof. Hongming Xu (Fellow of SAE & IMechE)**.  I also hold an **MEng in Vehicle Engineering** from **Jilin University** and a **BEng from Wuhan University of Technology**.  Currently, I am pursuing an **MSc in Computer Science (OMSCS)** at the **Georgia Institute of Technology**.

<!-- **Total Citations: <span id='total_cit'>77</span>** -->

# 🎯 Research Interests

- **Reinforcement Learning and Large Models**:  
  Multi-Agent RL; Energy Optimization; Safe & Efficient Control; Foundation Models for Intelligent Vehicles

- **Trustworthy & Autonomous Systems**:  
  Safety-Critical AI; Digital Twin Simulation; AI-driven Vehicle Stability and Control

- **Machine Learning for Intelligent Transportation**:  
  Self-supervised Learning; Model-based & Data-driven Vehicle Estimation; Multi-sensor Fusion
  
If you are interested in academic collaboration or discussion, please feel free to contact me huam12140 [AT]  gmail.com.

# 🔥 News
- *2025.11*: &nbsp;🎉🎉 Invited as a reviewer for [TMLR](https://jmlr.org/tmlr/).
- *2025.10*: &nbsp;🎉🎉 Invited as a reviewer for ICLR 2026, CVPR 2026, [TNNLS](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=5962385).
- *2025.09*: &nbsp;🎉🎉 Invited as a reviewer for [Pattern Recognition](https://www.sciencedirect.com/journal/pattern-recognition) and [IEEE Trans. on Reliability](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=24).
- *2025.08*: &nbsp;🎉🎉 I will be starting my CS Ph.D. in [BDSC Lab](https://bdsc-uic.github.io/index.html) at the University of Illinois Chicago, under the supervision of Prof. [Philip S. Yu](https://scholar.google.com/citations?user=D0lL1r0AAAAJ).
- *2025.04*: &nbsp;🎉🎉 Give a talk at [Xtra Computing Group](https://www.xtra.science/) of Prof. [Bingsheng He](https://www.comp.nus.edu.sg/~hebs/) at School of Computing, NUS.
- *2025.03*: &nbsp;🎉🎉 I've been awarded the Outstanding Graduate in Zhejiang Province and Outstanding Graduate at Zhejiang University.
- *2025.02*: &nbsp;🎉🎉 [Invisible Backdoor Attack in Self-supervised Learning](https://arxiv.org/abs/2405.14672) (First author) is accepted by CVPR 2025.
- *2025.01*: &nbsp;🎉🎉 [Agent Security Bench (ASB): Formalizing and Benchmarking Attacks and Defenses in LLM-based Agents](https://arxiv.org/abs/2410.02644) (First author) is accepted by ICLR 2025.
- *2025.01*: &nbsp;🎉🎉 [Class Incremental Fault Diagnosis under Limited Fault Data via Supervised Contrastive Knowledge Distillation](https://arxiv.org/pdf/2501.09525) (First author) is accepted by IEEE Transactions on Industrial Informatics.
- *2024.11*: &nbsp;🎉🎉 I've been awarded the National Scholarship for Graduate Students at Zhejiang University.
- *2024.04*: &nbsp;🎉🎉 [Generalized Out-of-distribution Fault Diagnosis (GOOFD) via Internal Contrastive Learning](https://ieeexplore.ieee.org/abstract/document/10510599) (Co-first author) is accepted by IEEE Transactions on Industrial Informatics.
- *2023.11*: &nbsp;🎉🎉 I've been awarded the National Scholarship for Graduate Students at Zhejiang University.

# 📖 Educations
- **University of Birmingham** | Jun. 2021 -- May. 2025 <br>
  Ph.D. in Engineering, United Kingdom <br>
  Supervisor: Prof. Hongming Xu <br>
  Thesis: *Multi-scale Energy Management for Multi-mode Hybrid Vehicles using Reinforcement Learning*

- **Georgia Institute of Technology** | Jan. 2023 -- Present <br>
  Online Master of Science in Computer Science (OMSCS), USA <br>
  Core Courses: Deep Learning; AI for Robotics; Reinforcement Learning

- **Jilin University** | Sep. 2016 -- Jun. 2019 <br>
  MEng. in Vehicle Engineering (with honors), China <br>
  Advisor: Prof. Changfu Zong <br>
  Thesis: *Research on Autonomous Tracking Control of Intelligent Full Drive-by-Wire Electric Vehicle* <br>
  🏅 *Excellent Graduation Thesis Award*

- **Wuhan University of Technology** | Sep. 2012 -- Jun. 2016 <br>
  BEng. in Vehicle Engineering (with honors), China <br>
  Advisor: Prof. Miaohua Huang <br>
  Thesis: *Design of the Steer-by-Wire Control System for the Caravan*

  
# 📝 Publications

- [Communication-Efficient MARL for Platoon Stability and Energy-Efficiency Co-Optimization in Cooperative Adaptive Cruise Control of CAVs](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10777569), **Min Hua**, D. Chen, K. Jiang, F. Zhang, B. Wang, Q. Zhou, H. Xu, *IEEE Transactions on Vehicular Technology*, 74(4):6076–6087, 2025.  
- [Energy Management of Multi-Mode Plug-in Hybrid Electric Vehicle Using Multi-Agent Deep Reinforcement Learning](https://www.sciencedirect.com/science/article/pii/S0306261923008905), **Min Hua**, C. Zhang, F. Zhang, Z. Li, X. Yu, H. Xu, Q. Zhou, *Applied Energy*, 348:121526, 2023.  
- [Multi-Agent Reinforcement Learning for Connected and Automated Vehicles Control: Recent Advancements and Future Prospects](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11016811), **Min Hua**, D. Chen, X. Qi, K. Jiang, Z.E. Liu, Q. Zhou, H. Xu, *IEEE Transactions on Automation Science and Engineering*, 22:16266–16286, 2025.  
- [Efficient Energy Management of Plug-in Hybrid Electric Vehicles through Ensemble with In-target Minimization Q-learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11036253), **Min Hua** et al., *IEEE Transactions on Transportation Electrification*, Early Access, 2025.  
- [High Precision Data-Mechanism-Driven Lateral Velocity Estimation Using Transfer Learning in Distributed Vehicles](https://ieeexplore.ieee.org/document/10899887), G. Chen, **M. Hua***, *IEEE Transactions on Instrumentation & Measurement*, 2025.  
- [Lane Change Trajectory Prediction Considering Driving Style Uncertainty for Autonomous Vehicles](https://doi.org/10.1016/j.ymssp.2024.110854), **M. Hua*** et al., *Mechanical Systems and Signal Processing*, 206:110854, 2024.  
- [Optimal Energy Management of Plug-in Hybrid Vehicles Through Exploration-to-Exploitation Ratio Control in Ensemble Reinforcement Learning](https://ieeexplore.ieee.org/document/10761122), B. Shuai†, **M. Hua†**, Y. Li, S. Shuai, H. Xu, Q. Zhou, *IEEE Transactions on Intelligent Vehicles*, Early Access, 2024. (†Equal contribution)  
- [A Systematic Survey of Control Techniques and Applications in Connected and Automated Vehicles](https://ieeexplore.ieee.org/document/10167961), W. Liu†, **M. Hua†**, Z. Deng, Z. Meng, Y. Huang, C. Hu, X. Xia, *IEEE Internet of Things Journal*, 10(24):21892–21916, 2023. (†Equal contribution)  
- [Multi-Level Decision Framework Collision Avoidance Algorithm in Emergency Scenarios](https://doi.org/10.1504/IJVD.2024.134857), **M. Hua***, G. Chen, X. Wang, *International Journal of Vehicle Design*, 95(3–4):155–185, 2024.  
- [Comprehensive Chassis Control Strategy of FWIC-EV Based on Sliding Mode Control](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/iet-its.2018.5244), **M. Hua*** et al., *IET Intelligent Transport Systems*, 13(4):703–713, 2019.  
- [A Hierarchical Energy Efficiency Optimization Control Strategy for Distributed Electric Vehicles](https://journals.sagepub.com/doi/10.1177/0954407018765671), **M. Hua*** et al., *Proc. IMechE, Part D: Journal of Automobile Engineering*, 233(3):605–621, 2019.  
- [Research on Synchronous Control Strategy of Steer-by-Wire System with Dual Steering Actuator Motors](https://www.inderscienceonline.com/doi/abs/10.1504/IJVAS.2020.10028006), **M. Hua*** et al., *International Journal of Vehicle Autonomous Systems*, 15(1):50–76, 2020.  


📘 *For the complete publication list, please visit my [Google Scholar](https://scholar.google.com/citations?user=0t66bQYAAAAJ&hl=zh-CN).*


# 🎖 Honors and Awards
- 🥇 *Best Paper Award*, IEEE ITSC 2024  
- 🥈 *Best Paper Award*, IEEE IV 2024 Workshop  
- 🥈 *Silver Prize*, International “Internet+” Innovation Competition, 2021  
- 🎓 *University of Birmingham Scholarship* (2021–2025)  
- 🏅 *Outstanding Employee*, SAIC Motor Passenger Vehicle Co. (2019)
- 
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 


# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
