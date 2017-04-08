# RL-Tutorial
THU-FIT Reinforcement Learning tutorials


# Week 7

## Abstract

-	Double Q Network, Prioritized Replay, Dueling Network
-	Actor-Critic Method
-	DPG/DDPG, A3C

## Discussion

#### TODO

-	为什么minibatch要不相关/独立同分布？取同一个序列上的连续状态能不能起到快速迭代的效果？
-	Dueling Network能起到多大的提升？

#### Solved

-	Q'和Q具体是什么关系？
	+	前者是后者的平滑

## References

<ul>
	<li><a href="https://github.com/dennybritz/reinforcement-learning">RL系列资源，含电子书、笔记、习题与解答</a></li>
	<li><a href="https://github.com/yanpanlau/DDPG-Keras-Torcs">300行DDPG</a></li>
	<li><a href="https://github.com/NVlabs/GA3C">Nvidia A3C</a></li>
</ul>


## Papers
<ul>
	<li><a href="https://arxiv.org/abs/1511.06581">Dueling Network</a></li>
	<li><a href="https://arxiv.org/abs/1509.02971">DDPG</a></li>
	<li><a href="https://arxiv.org/abs/1602.01783">A3C</a></li>
</ul>


---

# Week 6

## Abstract

-	DQN原理与实践
-	如何在服务器上训一个RL模型

## References
<ul>
	<li><a href="http://www.algorithmdog.com/series/rl-series">强化学习系列教程</a></li>
	<li><a href="https://zhuanlan.zhihu.com/intelligentunit">DQN从入门到放弃 - 知乎专栏</a></li>
	<li><a href="http://pytorch.org/">PyTorch官网</a></li>
	<li><a href="https://www.tensorflow.org/">TensorFlow官网</a></li>
	<li><a href="https://gym.openai.com/">OpenAI gym</a></li>
	<li><a href="https://github.com/yenchenlin/DeepLearningFlappyBird">DQN Flappy Bird</a></li>
</ul>

## Papers
<ul>
	<li><a href="https://arxiv.org/abs/1312.5602">DQN原始paper</a></li>
	<li><a href="https://storage.googleapis.com/deepmind-media/dqn/DQNNaturePaper.pdf">DQN Nature paper</a></li>
	<li><a href="https://arxiv.org/abs/1509.06461">Double Q-Network</a></li>
	<li><a href="https://arxiv.org/abs/1511.06581">Dueling Network</a></li>
	<li><a href="https://arxiv.org/abs/1509.02971">Action集合是连续的情况，使用的是Actor-Critic</a></li>
	<li><a href="https://arxiv.org/pdf/1608.02192v1.pdf">GTA那篇paper（笑）</a></li>
</ul>
