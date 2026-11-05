<img width="1400" height="350" alt="hdidibanner" src="https://github.com/user-attachments/assets/d82cf7f5-eb6e-4e40-8d3f-2ced7fb6cef1" />

## Last projects

### [NIMA HAT One](https://nimarobotics.com). | Modular Research Platform for Human-Robot Interaction

https://github.com/user-attachments/assets/40a41241-aebe-4684-b901-9a11d1cb8802

**An extensible framework for exploring social perception, expressive behavior, and embodied intelligence in humanoid robots.**

> **Research Vision**
>
> NIMA (Natural Interaction through Memorable Animation) is an independent research and development project exploring how modular, perception-aware expressive systems can enhance human-robot interaction.
>
> Beyond expressive animation, NIMA aims to provide a **flexible research platform built around interchangeable components and standardized interfaces**, enabling researchers to develop, replace, and evaluate different approaches to perception, cognition, attention, and robotic behavior without redesigning the entire system.
>
> Its first physical implementation, **NIMA HAT One**, is an expressive hardware add-on for the Unitree G1, combining ocular animation, enhanced social perception, and multimodal interaction within a modular ROS 2 ecosystem.

**Core Principles & Research Directions**

- **Modular & Interchangeable:** Independent ROS 2 modules with standardized input/output interfaces, designed to support alternative algorithms, research approaches, and future extensions.
- **Research-Oriented Architecture:** A flexible environment for experimenting with social perception, attention, cognitive controllers, and expressive behavior.
- **Expressive Human-Robot Interaction:** Animation-inspired ocular expressions, gaze behavior, speech, and coordinated non-verbal communication.
- **Multiple Interaction Modes:** Support for manual puppeteering, predefined interaction sequences, and increasingly autonomous, perception-driven behaviors.
- **Embodiment & Scalability:** A reusable software ecosystem designed to bridge simulation, physical interfaces, and different robotic platforms.
- **Hardware Extensibility:** Physical add-ons that expand robotic capabilities while preserving compatibility with existing robot hardware.

**Development & Open-Source Roadmap**

NIMA is currently under active development, with its first physical prototype undergoing integration and testing on the Unitree G1.

The source code is currently private while the initial architecture and implementation are being consolidated. **The software framework is planned for progressive open-source release in the near future**, encouraging collaboration, experimentation, and contributions from the robotics research community.

Hardware designs and embedded firmware are currently intended to remain proprietary, while the modular software ecosystem will be developed with openness and extensibility in mind.

---

###  [HomeRobot](https://github.com/hugodidi/home_robot). ROS2-based modular system for autonomous indoor robotics.

https://github.com/user-attachments/assets/b2f15919-0bd3-4bd0-8e44-a74e1bf75ad5

* Real-time SLAM and navigation using Nav2
* Task-level control through finite state machines
* Integration with embedded systems (Arduino)
* Designed as a flexible playground for rapid robotics prototyping

---


### [rl_hnav](https://github.com/uleroboticsgroup/rl_hnav) (Contributing). Full-stack humanoid navigation and simulation pipeline for Unitree G1.

<img width="1280" height="640" alt="image" src="https://github.com/user-attachments/assets/a6e5baa6-bbf3-409e-b6c0-ad23d8e41b2c" />

- Extended ROS 2-based navigation pipeline integrating SLAM and Nav2 for humanoid locomotion  
- Designed MuJoCo → Gazebo synchronization pipeline for consistent state replication  
- Converted Gazebo into a real-time visualization layer (“puppet mode”) driven by MuJoCo  
- Resolved joint state desynchronization and timing issues affecting TF and control loops  
- Implemented joint state bridge with timestamp correction for ROS 2 compatibility  
- Optimized LiDAR configuration for stable SLAM and navigation  
- Designed deterministic launch orchestration for full system startup (Gazebo, SLAM, Nav2)  
- Addressed sim-to-real inconsistencies in collision modeling and physics behavior  
- Mitigated odometry drift caused by impact noise during dynamic locomotion

