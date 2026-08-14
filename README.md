# Trix-AD
**A Unified Kinematic Model + Explainable 3D Q-Learning Framework**

One single equation → Parallel Parking as well as overtaking

[![GitHub stars](https://img.shields.io/github/stars/aibgr/3DQ-Park?style=social)](https://github.com/aibgr/3DQ-Park/stargazers)
[![IEEE T-IV](https://img.shields.io/badge/IEEE%20T--IV-Submitted%20%202026-blue)](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=7274857)
[![Webots 2025](https://img.shields.io/badge/Simulated-Webots%202025-orange)](https://cyberbotics.com)



> First paper of the **Trix Series** in preparation for **IEEE Transactions on Intelligent Vehicles** – 2026
> First-round decision expected: early 2026
> Full source code will be released immediately upon acceptance of all Trix Series.

### Key Features
- Single kinematic formulation covering **all** parking maneuvers + overtaking
- Guided 3D Q-Learning with hierarchical 8-cube exhaustive search
- Average convergence in under 40 episodes
- Real-time inference (< 15 ms on CPU)
- Full 3D mechanical simulation in Webots with accurate BMW i3 dynamics
- Successfully parks on **both left and right sides** of the road

Map parser → parking slot detection → α-space search → spatial path generation → Webots controller → trajectory validation

### Results (Webots R2023b)

<table>
<tr>
<td align="center"><img src="https://github.com/user-attachments/assets/e302219c-2ff0-46a6-abd4-5eb52be8848e" alt="Training convergence & α-space exploration"></td>
<td align="center"><img src="https://github.com/user-attachments/assets/54cb8169-4038-44db-b170-c880763b6fad" alt="Left-side parallel parking"></td>
</tr>
<tr>
<td align="center"><img src="https://github.com/user-attachments/assets/f2fa273d-29b5-4580-bc75-e5dee4ebf25b" alt="Right-side parallel parking"></td>
<td align="center"><img src="https://github.com/user-attachments/assets/bbdb739e-1bce-4d0a-a72b-338ebad27f05" alt="Complete parking sequence"></td>
</tr>
</table>

<p align="center">


https://github.com/user-attachments/assets/610a60ad-527d-4daf-865d-39a4d2f36edf


https://github.com/user-attachments/assets/25ec0aac-48a1-42eb-9e0a-8f37fcaa3551


https://github.com/user-attachments/assets/9cf9c246-719c-4560-ac8a-8685ff81ec42



<em>* Three videos showcase real-time Trix Capability
</em>
</p>

## Project Status

- `v1.0.0`: parking-only baseline documented and validated
- `feature/overtaking`: under active development in the private code repository
- Public repository currently contains documentation, media, and selected reproducible assets
- Full research code will be released after publication or upon collaboration agreement

### Coming Soon
- Trix-Overtaking (manuscript in preparation as well as Trix as a compelete work package)
- Real-world deployment on full-scale autonomous vehicle (LiDAR + camera + ultrasonics)
- ROS 2 + NVIDIA Jetson implementation

### Author
**A. Bagheri**
B.Sc. Mechanical Engineering & Computer Engineering – Iran University of Science and Technology, 2026

GitHub: @aibgr | LinkedIn: @aibgr

**Supervisor:** Dr. Seyed Hassan Zabihifar – Iran University of Science and Technology

If you find this work useful, please give it a ⭐
Full source code will be made public immediately after publication of the Trix series.

**More exciting updates coming very soon!**
