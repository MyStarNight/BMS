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
time series forecasting(TRF)

## 调研疑惑

怎么大家都用RL来打游戏呢？

## repositories

### **[street-fighter-ai](https://github.com/linyiLYi/street-fighter-ai)**

本项目基于深度强化学习训练了一个用于通关《街头霸王·二：冠军特别版》（Street Fighter II Special Champion Edition）关底 BOSS 的智能 AI 代理。

该智能代理完全基于游戏画面（RGB 像素值）进行决策，在该项目给定存档中最后一关的第一轮对局可以取得 100% 胜率（实际上出现了“过拟合”现象，详见[运行测试](https://zhuanlan.zhihu.com/p/623286329/edit#running-tests)部分的讨论）。
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTEzOTc0OTk4OSwxMDA0MDczODMzLDQxMT
c4NDI5OCwxNjY0MjEwNzQxLC03NTQ4ODkyODBdfQ==
-->