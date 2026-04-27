# Hi, I'm Kyaw Linn Khant

**Robotics & AI Engineer** — I build systems that move, perceive, and decide.

From implementing SLAM algorithms from scratch to training quadruped walking policies via sim-to-real transfer, I work across the full stack: state estimation, reinforcement learning, multi-agent systems, and edge deployment.

---

## What I build

| Area | Projects |
|------|----------|
| **SLAM / Perception** | EKF SLAM (TurtleBot3), 2D LiDAR landmark detection, Taubin circle fitting |
| **Reinforcement Learning** | Sim2Real quadruped (Isaac Lab → hardware), self-balancing robot (MuJoCo → TFLite MCU) |
| **Multi-Agent Systems** | MAPF with CBS + MARL (transformer communication, CBS-bootstrapped curriculum) |
| **Swarm Robotics** | Decentralised drone swarm cooperative transport (no inter-drone communication) |
| **Edge AI** | YOLO on Raspberry Pi, ONNX → TFLite int8 at 200Hz on Teensy 4.1 |
| **Autonomous Agents** | LangGraph SRE agent for self-healing Kubernetes clusters |

---

## Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![ROS2](https://img.shields.io/badge/ROS_2-22314E?style=flat-square&logo=ros&logoColor=white)
![Isaac Lab](https://img.shields.io/badge/Isaac_Lab-76B900?style=flat-square&logo=nvidia&logoColor=white)
![MuJoCo](https://img.shields.io/badge/MuJoCo-FF6B35?style=flat-square)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)

---

## Featured projects

### [MAPF-CBS + MARL](https://github.com/KyawLinnKhant/mapf-cbs)
Multi-agent path finding: optimal CBS baseline + MAPPO with transformer attention, CBS-bootstrapped curriculum, and lifelong goals. Pure Python · No ROS · Mac-native.

### [Sim2Real Quadruped](https://github.com/KyawLinnKhant/sim2real-quad)
12-joint walking robot trained in NVIDIA Isaac Lab via PPO, deployed on 3D-printed hardware through ROS 2 + Arduino. No hand-coded gaits.

### [EKF SLAM — TurtleBot3](https://github.com/KyawLinnKhant/slam_turtlebot_ros)
Full SLAM stack from scratch: Taubin circle fitting for landmark detection, Mahalanobis-gated data association, EKF predict/correct loop. ROS 2 · C++.

### [Self-Balancing Robot RL](https://github.com/KyawLinnKhant/IMP_MJC_RL)
MuJoCo simulation to PPO policy to ONNX to TFLite int8 to Teensy 4.1 at 200Hz. Full sim-to-real pipeline with algorithm comparison.

### [Drone Swarm Transport](https://github.com/KyawLinnKhant/Swarm_Drones_ROSCS)
Decentralised multi-UAV cooperative payload transport. No explicit inter-drone communication — emergent coordination via layered behaviours.

### [Chameleon-SRE](https://github.com/KyawLinnKhant/Chameleon_SRE)
Autonomous AI agent that monitors, diagnoses, and self-heals Kubernetes clusters using LangGraph + local LLM (Ollama). 100% local, zero cloud cost.

---

## Currently

Training MARL agents on procedurally generated MAPF environments and exploring CBS-bootstrapped curriculum learning for multi-agent coordination.

Open to **Robotics Engineer / Research Engineer / Applied AI** roles in **Singapore, Australia, New Zealand, Thailand**.

---

[Portfolio](https://kyawlinnkhant.github.io/my_portfolio/) · [LinkedIn](https://www.linkedin.com/in/kyawlinnkhant)
