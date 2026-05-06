<img width="1400" height="350" alt="hdidibanner" src="https://github.com/user-attachments/assets/d82cf7f5-eb6e-4e40-8d3f-2ced7fb6cef1" />

---

## Last projects
###  [HomeRobot](https://github.com/hugodidi/home_robot). ROS2-based modular system for autonomous indoor robotics.

* Real-time SLAM and navigation using Nav2
* Task-level control through finite state machines
* Integration with embedded systems (Arduino)
* Designed as a flexible playground for rapid robotics prototyping

https://github.com/user-attachments/assets/b2f15919-0bd3-4bd0-8e44-a74e1bf75ad5

---

### [ANIMA](https://github.com/hugodidi/anima). Expressive interface framework for human-robot interaction based on affective animation and social perception.

> **Research Direction**  
> ANIMA (Affective Natural Interaction through Memorable Animation) explores how animation-inspired expressive interfaces can enhance social presence, affective legibility and memorable interaction in humanoid robots. The project focuses especially on ocular expression as a core channel for non-verbal communication, while considering body gesture as a complementary and scalable expressive dimension.

* Parametric ocular expression model for gaze, blinking, eyelid aperture, pupil dynamics, asymmetry and expressive timing
* Animation-inspired design approach that prioritizes expressive legibility over anatomical facial realism
* Real-time simulation and monitoring interface for designing, testing and debugging robot expressive states
* ROS 2-oriented modular architecture for manual control, puppet control, perception inputs and future cognitive controllers
* Designed as an expressive HRI layer, currently under development using the Unitree G1 as a case study and reference platform
  
<img width="1773" height="922" alt="image" src="https://github.com/user-attachments/assets/70f4a4c0-54cb-42aa-9e0f-2be8228f8520" />

---

### [rl_hnav](https://github.com/uleroboticsgroup/rl_hnav) (Contributing). Full-stack humanoid navigation and simulation pipeline for Unitree G1.

- Extended ROS 2-based navigation pipeline integrating SLAM and Nav2 for humanoid locomotion  
- Designed MuJoCo → Gazebo synchronization pipeline for consistent state replication  
- Converted Gazebo into a real-time visualization layer (“puppet mode”) driven by MuJoCo  
- Resolved joint state desynchronization and timing issues affecting TF and control loops  
- Implemented joint state bridge with timestamp correction for ROS 2 compatibility  
- Optimized LiDAR configuration for stable SLAM and navigation  
- Designed deterministic launch orchestration for full system startup (Gazebo, SLAM, Nav2)  
- Addressed sim-to-real inconsistencies in collision modeling and physics behavior  
- Mitigated odometry drift caused by impact noise during dynamic locomotion

<img width="1280" height="640" alt="image" src="https://github.com/user-attachments/assets/a6e5baa6-bbf3-409e-b6c0-ad23d8e41b2c" />
