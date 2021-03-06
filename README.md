# DQN: Navigation
This project was provided by [the Deep Reinforcement Learning Nanodegree Course of Udacity.](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893) The agent was trained in Deep Q Network(DQN) developed by [DeepMind in 2015.](https://storage.googleapis.com/deepmind-media/dqn/DQNNaturePaper.pdf) It was able to solve a wide range of Atari games (some to superhuman level) by combining reinforcement learning and deep neural networks at scale. The algorithm was developed by enhancing a classic RL algorithm called Q-Learning with deep neural networks and a technique called experience replay.

# Environment
The project environment is similar to, but not identical to the Banana Collector environment on the Unity. For this project, We will install an amended version of the `python/` folder from the [ML-Agents repository](https://github.com/Unity-Technologies/ml-agents).  It has been edited to include a few additional pip packages needed for the Deep Reinforcement Learning Nanodegree program.<br/>

![Alt Text](https://video.udacity-data.com/topher/2018/June/5b1ab4b0_banana/banana.gif)

# The Goal of the Project
The goal is to train an agent to navigate (and collect bananas!) in a large, square world using deep Q network. 

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of the agent is to collect as many yellow bananas as possible while avoiding blue bananas. The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

The state space has 37 dimensions and contains the agent's velocity, along with the perception of objects forward. Given this information, the agent has to learn how to best select actions. Four discrete actions are available:

``0`` - move forward <br/>
``1`` - move backward <br/>
``2`` - turn left <br/>
``3`` - turn right <br/>

# Dependencies
Python==3.x+ [install](https://www.python.org/downloads/) <br/> 
Pytorch==0.4.0+ [install](https://pytorch.org/get-started/locally/) <br/>
ml-agents==0.27.0+ [install](https://pypi.org/project/mlagents/)<br/>
tensorflow==1.7.1 <br/>
Pillow>=4.2.1 <br/>
matplotlib <br/>
numpy>=1.11.0 <br/>
jupyter <br/>
pytest>=3.2.2 <br/>
docopt <br/>
pyyaml <br/>
protobuf==3.5.2 <br/>
grpcio==1.11.0 <br/>
torch==0.4.0
pandas<br/>
scipy<br/>
ipykernel<br/>

# The Repository Structure
* ``Navigation.ipynb`` - Includes the environment, agent, model, and DQN functions.<br/>
* ``Report.md`` - Includes hyperparameters.<br/>
* ``reward_plot.png`` - Shows the cumulative rewards after training.<br/>
* ``checkpoint.pth`` - Contains the training weights of the Q network.<br/>
