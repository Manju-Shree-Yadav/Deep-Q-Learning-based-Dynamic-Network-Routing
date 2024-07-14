# Deep-Q-Learning-based-Dynamic-Network-Routing
### Problem Statement
Traditional network routing algorithms often fail to adapt dynamically to changing network conditions, leading to suboptimal performance in terms of latency, packet loss, and throughput. This project aims to develop a robust dynamic network routing algorithm using Deep Q-Learning (DQL) that can optimize these metrics and ensure efficient packet transfer even under varying network conditions.
### Literature Review
Dynamic routing algorithms have been extensively studied, with traditional methods including Dijkstra's and Bellman-Ford algorithms. However, these methods lack the adaptability required for modern network environments. Reinforcement Learning (RL), specifically Deep Q-Learning, offers a promising approach to dynamically adjust routing decisions based on real-time network conditions, leveraging experience to optimize performance.
### System Architecture
The architecture consists of several key components:

**Network Environment:** Simulates the network topology and provides state information.
**DQN Agent:** Interacts with the network environment, making decisions based on the current state.
**Deep Q-Network (DQN):** A neural network used to approximate the Q-values for state-action pairs.
**Replay Memory:** Stores experiences for experience replay, stabilizing training.
### Tools/APIs Used
**Python:** The main programming language used.
**Keras:** For building the Deep Q-Network.
**NumPy:** For numerical computations.
**Matplotlib:** For plotting and visualization.
**NetworkX:** For network topology creation and manipulation.

How to Run
Clone the repository:

sh
Copy code
git clone https://github.com/your_username/dql-network-routing.git
cd dql-network-routing
Install dependencies:

sh
Copy code
pip install -r requirements.txt
