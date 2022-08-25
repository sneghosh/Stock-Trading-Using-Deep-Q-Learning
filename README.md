# Stock-Trading-Using-Deep-Q-Learning
Prepare an agent by implementing Deep Q-Learning that can perform unsupervised trading in stock trade. The aim of this project is to train an agent that uses Q-learning and neural networks to predict the profit or loss by building a model and implementing it on a dataset that is available for evaluation.
The stock trading index environment provides the agent with a set of actions:
Buy
Sell
Sit
This project has following sections:
Import libraries
Create a DQN agent
Preprocess the data
Train and build the model
Evaluate the model and agent 
Steps to perform
In the section create a DQN agent, create a class called agent where:
Action size is defined as 3
Experience replay memory to deque is 1000
Empty list for stocks that has already been bought
The agent must possess the following hyperparameters:
gamma= 0.95
epsilon = 1.0
epsilon_final = 0.01
epsilon_decay = 0.995
Note: It is advised to compare the results using different values in hyperparameters.
Neural network has 3 hidden layers
Action and experience replay are defined
