# Deep-Q-Learning-based-Dynamic-Network-Routing
### Problem Statement
Traditional network routing algorithms often fail to adapt dynamically to changing network conditions, leading to suboptimal performance in terms of latency, packet loss, and throughput. This project aims to develop a robust dynamic network routing algorithm using Deep Q-Learning (DQL) that can optimize these metrics and ensure efficient packet transfer even under varying network conditions.
### Literature Review
Dynamic routing algorithms have been extensively studied, with traditional methods including Dijkstra's and Bellman-Ford algorithms. However, these methods lack the adaptability required for modern network environments. Reinforcement Learning (RL), specifically Deep Q-Learning, offers a promising approach to dynamically adjust routing decisions based on real-time network conditions, leveraging experience to optimize performance.
### System Architecture
The architecture consists of several key components:

**Network Environment:** Simulates the network topology and provides state information.<br/>
**DQN Agent:** Interacts with the network environment, making decisions based on the current state.<br/>
**Deep Q-Network (DQN):** A neural network used to approximate the Q-values for state-action pairs.<br/>
**Replay Memory:** Stores experiences for experience replay, stabilizing training.<br/>
### Tools/APIs Used
**Python:** The main programming language used.<br/>
**Keras:** For building the Deep Q-Network.<br/>
**NumPy:** For numerical computations.<br/>
**Matplotlib:** For plotting and visualization.<br/>
**NetworkX:** For network topology creation and manipulation.<br/>
### Results
The DQN agent successfully learns to optimize routing paths, reducing latency and packet loss.<br/>
The system adapts to network changes dynamically, finding alternative paths when the optimal path is down.<br/>

### Contributors
Manju Shree Yadav - manjushreeyd.cs23@rvce.edu.in

