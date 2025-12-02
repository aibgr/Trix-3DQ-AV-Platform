# 3DQ-Park  
**A Unified Trigonometric Kinematic Model + Guided 3D Q-Learning Framework for All Parking Maneuvers & Overtaking**

[![GitHub stars](https://img.shields.io/github/stars/aibgr/3DQ-Park?style=social)](https://github.com/aibgr/3DQ-Park/stargazers)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Webots](https://img.shields.io/badge/Simulated%20in-Webots%202023-orange)](https://cyberbotics.com)

> **One single kinematic equation** → Parallel parking (both left & right side), perpendicular, angled, and overtaking  
> **One fast RL decision-maker** → Guided 3D Q-Learning with hierarchical 8-way cube search  
> **Fully mechanical 3D simulation** → Webots R2023b with accurate BMW i3 kinematics, friction, and actuator limits  

This repository contains the **first released part** of the **3DQ Series**.  
The complete method (including overtaking, real-time implementation, and experimental validation) is currently under review and in follow-up papers.

**First paper (3DQ-Park)** submitted to **IEEE Transactions on Intelligent Vehicles** — Nov 2025  
**First-round decision expected:** Dec 2025 – Jan 2026  
Source code will be made fully public immediately after acceptance of the series.

### Highlights
- Successfully parks on **both sides of the road** in complex urban scenes  
- Zero hand-crafted rules — pure learning-based decision making  
- Convergence in < 40 episodes on average  
- Real-time capable (< 15 ms per decision on CPU)  
- Ready for transfer to our full-scale autonomous platform (LiDAR + camera + ultrasonics)

### Simulation Results (Webots)

<table>
  <tr>
    <td align="center"><img src="https://github.com/user-attachments/assets/a4b93d95-1d00-41ac-9105-7c95f897c201" alt="Final result"></td>
    <td align="center"><img src="https://github.com/user-attachments/assets/bd473969-7df3-49f7-ad3f-5e3e214251cb" alt="Plasma jet demo – wait, wrong repo 😂"></td>
    <td align="center"><img src="https://github.com/user-attachments/assets/2922ab8e-79b1-46ad-9e40-b84fdbf30da8" alt="Back view of vehicle"></td>
  </tr>
  <tr>
    <td align="center"><img src="https://github.com/user-attachments/assets/e302219c-2ff0-46a6-abd4-5eb52be8848e" alt="Training convergence"></td>
    <td align="center"><img src="https://github.com/user-attachments/assets/54cb8169-4038-44db-b170-c880763b6fad" alt="Left-side parallel parking"></td>
    <td align="center"><img src="https://github.com/user-attachments/assets/f2fa273d-29b5-4580-bc75-e5dee4ebf25b" alt="Right-side parallel parking"></td>
  </tr>
</table>

<p align="center">
  <img src="https://github.com/user-attachments/assets/bbdb739e-1bce-4d0a-a72b-338ebad27f05" alt="Complete parking sequence"/>
  <br><em>Full autonomous parking sequence (right side) – from detection to final pose</em>
</p>

### Upcoming in the 3DQ Series
- 3DQ-Overtaking (under preparation)  
- Real-world experiments on our full-size autonomous vehicle  
- ROS2 + NVIDIA Jetson deployment  

### Author
**Ali Bagheri**  
B.Sc. Mechanical Engineering & Computer Engineering (Minor)  
Iran University of Science and Technology, 2025  

**Contact:** [AliBagheri79.ab@gmail.com](mailto:AliBagheri79.ab@gmail.com)  
**LinkedIn:** [Ali Bagheri](https://www.linkedin.com/in/ali-bagheri-)  
**GitHub:** [@aibgr](https://github.com/aibgr)

**Supervisor:** Dr. Hassan Zabihi, IUST  

If you use this work or find it useful, please ⭐ the repo and cite our upcoming paper (bibtex will be added upon acceptance).

**Thank you for visiting!**  
More to come very soon
