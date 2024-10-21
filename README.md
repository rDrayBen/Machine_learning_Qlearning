# Q-Learning Agent for Pendulum Control
This project implements a Q-Learning agent to solve the Pendulum-v1 environment from OpenAI Gym. The agent is designed to learn optimal actions for balancing a pendulum in an upright position, using reinforcement learning methods.

Key Features:
* Deep Q-Learning Agent: This implementation utilizes a deep Q-learning agent with neural networks to approximate Q-values for continuous action spaces.
* Pendulum-v1 Environment: The agent is trained and evaluated in the Pendulum-v1 environment, where the goal is to balance a pendulum as close to the upright position as possible while minimizing the torque applied.
* Model Loading and Evaluation: The notebook includes functionality to load pre-trained models and evaluate the agent's performance over a series of episodes.
* Performance Metrics: Average scores are computed over multiple episodes to evaluate the effectiveness of the agent.
  
Workflow:
* Agent Initialization: The agent is initialized with state and action space sizes, and a Q-network architecture is created to approximate the action-value function.
* Action Selection: For each state, the agent selects an action based on its current Q-values using a policy such as ε-greedy or deterministic policy (for evaluation).

Training and Evaluation:
The agent interacts with the environment, taking actions and observing rewards and new states.
A pre-trained model can be loaded, and the agent can be evaluated over multiple episodes to observe its performance.

Methods:
Deep Q-Network (DQN): A neural network is used to approximate the Q-values for continuous action spaces.
Training Loop: The agent learns over multiple episodes by interacting with the environment and updating its Q-values using the Bellman equation.
Evaluation: The notebook includes functions to evaluate the agent's performance, calculating the average score over 100 episodes.

Demo:
![](https://github.com/Your_Repository_Name/Your_GIF_Name.gif)
