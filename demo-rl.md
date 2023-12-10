# some reinforcement learning codes

查找的主要目标方向为**deep reinforcement learning**;并且我们的主要目标为 **Model -free reinforcement learning**。

在这其中典型的算法代表如下：

1. Q-Learning with Function Approximation (Deep Q Networks - DQN):
DQN是一种基于Q-learning的深度强化学习算法，使用深度神经网络来估计Q值。它通过经验回放（experience replay）和目标网络（target network）来提高稳定性和收敛性。
2. Policy Gradient Methods:
这类算法直接学习策略，而不是学习值函数。其中的代表性算法包括：REINFORCE: 使用蒙特卡洛采样来估计梯度，更新策略以最大化长期回报。Proximal Policy Optimization (PPO): 通过限制更新步长，使得每次更新都不会改变策略太多，提高算法的稳定性。Trust Region Policy Optimization (TRPO): 通过引入约束来确保每次更新都在一个可接受的范围内。
3. Actor-Critic Methods:
这类算法同时学习策略和值函数。其中的代表性算法包括：Deep Deterministic Policy Gradients (DDPG): 适用于连续动作空间，结合了actor（策略）和critic（值函数）。Twin Delayed DDPG (TD3): 对DDPG进行改进，通过引入两个critic网络和延迟更新策略，提高学习的稳定性。
5. Trust Region Methods:
除了TRPO，还有一些其他使用trust region思想的算法，如Trust Region Policy Optimization (TRPO)和Natural Policy Gradient (NPG)。
6. Off-policy Algorithms:
除了DQN，还有其他一些重要的离线学习算法，如Off-policy Policy Evaluation (OPE)，用于估计一个给定策略的性能。
7. Soft Actor-Critic (SAC):
SAC是一种基于最大熵理论的强化学习算法，旨在同时优化预期回报和策略熵，以鼓励探索和提高鲁棒性。

## key words

deep reinforcement learning(DRL)
model-free reinforcement learning (MFRL)
time series forecasting(
<!--stackedit_data:
eyJoaXN0b3J5IjpbNTE3NzAwMDc1LDE2NjQyMTA3NDEsLTc1ND
g4OTI4MF19
-->