# Reinforcement Learning Agents

* [Deep Q-Learning](https://github.com/AdalbertoCq/Reinforcement-Learning-Agents/blob/master/deep_q_learning_cartpole_v0.ipynb):
  * Based on [V.Mnih et al. "Playing Atari with Deep Reinforcement Learning", 2013](https://arxiv.org/pdf/1312.5602.pdf)
  * Deep Q-Learning implementation.
  * Implementations of neural network action-value approximator in TensorFlow.
  * Implemented experience replay memory and fixed Q targets.
  * CartPole v0 OpenAI gym Q Rewards & Q value NN loss.
  ![CartPole v0 OpenAI gym Q Rewards](https://github.com/AdalbertoCq/Reinforcement-Learning-Agents/blob/master/dql_rewards.png "CartPole v0 OpenAI gym")
  ![CartPole v0 OpenAI gym Q value NN loss](https://github.com/AdalbertoCq/Reinforcement-Learning-Agents/blob/master/dql_loss.png "CartPole v0 OpenAI gym")

  
* [Double Deep Q-Learning](https://github.com/AdalbertoCq/Reinforcement-Learning-Agents/blob/master/double_deep_Q_learning_cart_pole_v0.ipynb):
  * Based on [H.Hasselt et al. "Deep Reinforcement Learning with Double Q-learning", 2015](https://arxiv.org/pdf/1509.06461.pdf)
  * Double Deep Q-Learning implementation.
  * Implemented experience replay memory and fixed Q targets.
  * Implemented two action-value neural network approximators, for action decision and fixed target.
  * CartPole v0 OpenAI gym Q Rewards & Q value NN loss.
  ![CartPole v0 OpenAI gym Q Rewards](https://github.com/AdalbertoCq/Reinforcement-Learning-Agents/blob/master/ddql_rewards.png "CartPole v0 OpenAI gym")
  ![CartPole v0 OpenAI gym Q value NN loss](https://github.com/AdalbertoCq/Reinforcement-Learning-Agents/blob/master/ddql_loss.png "CartPole v0 OpenAI gym")
  
* [Deep Deterministic Policy Gradient](https://github.com/AdalbertoCq/Reinforcement-Learning-Agents/blob/master/ddpg_mountain_car.ipynb):
  * Based on [T.Lillicrap et al. "Continuous control with deep reinforcement learning", 2016](https://arxiv.org/abs/1509.02971)
  * Deep Deterministic Policy Gradient implementation.
  * Implemented action repeat, experience replay memory and fixed targets for Actor/Critic Networks with soft update.
  * MountainCarContinuous-v0 solved after 70 episodes.
  * MountainCarContinuous-v0 Critic Loss and Rewards.
  ![MountainCarContinuous-v0 OpenAI gym Rewards](https://github.com/AdalbertoCq/Reinforcement-Learning-Agents/blob/master/ddpg_rewards.png "MountainCarContinuous-v0 OpenAI gym")
  ![MountainCarContinuous-v0 Q value NN Loss](https://github.com/AdalbertoCq/Reinforcement-Learning-Agents/blob/master/ddpg_critic_loss.png "MountainCarContinuous-v0 OpenAI gym")
