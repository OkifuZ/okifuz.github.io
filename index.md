---
layout: default
---

I'm currently pursuing Master's degree in CS at [VR lab](https://vrlab.buaa.edu.cn/), Beihang University, advised by Prof. [Junjun Pan](https://shi.buaa.edu.cn/junjun_pan), anticipate graduation in 2025. I obtained my Bachelor's degree in CS from Beihang University in 2022.

My research interests lies in Computer Graphics, Physics Based Animation. Specifically, (a) fast collision handling (b) leveraging AI to accelerate physical animations. 
Besides, I'm passionate about game development, seeking to bridge the gap between physics based animations and video games.

Email: siyanh [dot] zhu [at] gmail [dot] com

## Publication


Efficient frictional contacts for soft body dynamics via ADMM. **Siyan Zhu**, Cheng Fang, Peng Yu, [Xiao Zhai](https://zhai-xiao.github.io/), Aimin Hao & [Junjun Pan](https://shi.buaa.edu.cn/junjun_pan). The Visual Computer, 2024. 
[DOI](https://doi.org/10.1007/s00371-024-03438-8), [Video](https://www.youtube.com/watch?v=rUBcgffdxtQ), [Project](https://github.com/OkifuZ/admm-elasticity-contact-solver)..


## Experience

NetEase Games. Shanghai, 09.2024 - 11.2024(Expected). 
  *Game Engine Development Intern*. 
  Topics: realtime **physics destruction** with UE5 Chaos. 

Tencent IEG, Morefun Studio. Shenzhen, 05.2024 - 08.2024
  *Game Engine Development Intern*.
  Topics: performance analysis, optimization and effects improvement of **Unity dynamic bones/cloth** plugin. Implementation of deformed snow utilizing SRP.

miHoYo, Lumi. Shanghai, 06.2023 - 08.2023. 
  *Cloth Simulation Research Intern*.
  Topics: acceleration of high-precision **cloth simulation utilizing model order reduction(MOR) and neural networks**, and its application in games.

## Selected Projects

An interactive soft bodies solver (C++, oneTbb) [Video](https://www.youtube.com/watch?v=rUBcgffdxtQ)
  - A multi-threaded physics solver for soft bodies, supporting dense frictional contact between multi-layer fabrics.
  - The solver is achieved within ADMM optimization framework, utilizing projected dynamics and projected Gauss-Seidel.
  - Proximy query is implemented via BVH(embree) and root-parity CCD.
  

Simulator for soft tissue based on MPM with 2-level GPU acceleration (C++, CUDA)
  - Simulator is achieved via explicit material point method, supporting multi-material, cutting and fracture.
  - Using GPU SPGrid data structure to minimize the number of atomic operations for better performance.
  
Blustoon! (Unity3D) [project](github.com/OkifuZ/blustoon), [video](www.youtube.com/watch?v=5yirauGsRxo)
  - An independent game developed by me in 4 weeks, which stitches Animal Party and Splatoon to build a two-player party game.
  - Highlights: active rigdoll, ink splashing and coloring.