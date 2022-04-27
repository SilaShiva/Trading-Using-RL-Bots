# Trading-Using-RL-Bots

Reinforcement learning is a type of machine learning where there are environments and agents. These agents take actions to maximize rewards. Reinforcement learning has a very huge potential when it is used for simulations for training an AI model. There is no label associated with any data, reinforcement learning can learn better with very few data points. All decisions, in this case, are taken sequentially. The best example would be found in Robotics and Gaming.

## Trading

Trade is a basic economic concept involving the buying and selling of goods and services, with compensation paid by a buyer to a seller, or the exchange of goods or services between parties. Trade can take place within an economy between producers and consumers. International trade allows countries to expand markets for both goods and services that otherwise may not have been available. 

## Models
1. A2C

The actor critic algorithm consists of two networks (the actor and the critic) working together to solve a particular problem. At a high level, the Advantage Function calculates the agent’s TD Error or Prediction Error. The actor network chooses an action at each time step and the critic network evaluates the quality or the Q-value of a given input state. As the critic network learns which states are better or worse, the actor uses this information to teach the agent to seek out good states and avoid bad states.

2. DQN

DQN or Deep-Q Networks were first proposed by DeepMind back in 2015 in an attempt to bring the advantages of deep learning to reinforcement learning(RL), Reinforcement learning focuses on training agents to take any action at a particular stage in an environment to maximise rewards. Reinforcement learning then tries to train the model to improve itself and its choices by observing rewards through interactions with the environment.

3. PPO

Proximal Policy Optimization, or PPO, is a policy gradient method for reinforcement learning. The motivation was to have an algorithm with the data efficiency and reliable performance of TRPO, while using only first-order optimization. One detail to note is that when we apply PPO for a network where we have shared parameters for actor and critic functions, we typically add to the objective function an error term on value estimation and an entropy term to encourage exploration.
