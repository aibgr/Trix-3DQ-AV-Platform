# 3DQ-Park  
**A Unified Kinematic Model + Guided 3D Q-Learning Framework**  
One single equation → Parallel parking (both sides), perpendicular, angled, and overtaking

[![GitHub stars](https://img.shields.io/github/stars/aibgr/3DQ-Park?style=social)](https://github.com/aibgr/3DQ-Park/stargazers)
[![IEEE T-IV](https://img.shields.io/badge/IEEE%20T--IV-Submitted%20Nov%202025-blue)](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=7274857)
[![Webots 2023](https://img.shields.io/badge/Simulated-Webots%202023-orange)](https://cyberbotics.com)

> First paper of the **3DQ Series** submitted to **IEEE Transactions on Intelligent Vehicles** – November 2025  
> First-round decision expected: December 2025 – January 2026  
> Full source code will be released immediately upon acceptance of all 3DQ Series.

### Key Features (At First, Please review the Repository *.mp4 videos)
- Single kinematic formulation covering **all** parking maneuvers + overtaking  
- Guided 3D Q-Learning with hierarchical 8-cube exhaustive search  
- Average convergence in under 40 episodes  
- Real-time inference (< 15 ms on CPU)  
- Full 3D mechanical simulation in Webots with accurate BMW i3 dynamics  
- Successfully parks on **both left and right sides** of the road

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
  <em>*</em>
</p>

### Coming Soon
- 3DQ-Overtaking (manuscript in preparation)  
- Real-world deployment on full-scale autonomous vehicle (LiDAR + camera + ultrasonics)  
- ROS 2 + NVIDIA Jetson implementation

### Author
**Ali Bagheri**  
B.Sc. Mechanical Engineering & Computer Engineering (Minor) – Iran University of Science and Technology, 2025  
Email: AliBagheri79.ab@gmail.com | GitHub: [@aibgr](https://github.com/aibgr)  
LinkedIn: [ali-bagheri](https://www.linkedin.com/in/ali-bagheri-)  

**Supervisor:** Dr. Hassan Zabihi – Iran University of Science and Technology

If you find this work useful, please give it a ⭐  
Full source code will be made public immediately after publication of the 3DQ series.

**More exciting updates coming very soon!**
