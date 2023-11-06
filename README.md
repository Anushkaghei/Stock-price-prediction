# What is Reinforcement Learning?  
Reinforcement learning is another type of machine learning besides supervised and unsupervised learning. 
This is an agent-based learning system where the agent takes actions in an environment where the goal is to maximize the record. 
Reinforcement learning does not require the usage of labeled data like supervised learning.
Reinforcement learning works very well with less historical data. 
It makes use of the value function and calculates it on the basis of the policy that is decided for that action.

# Reinforcement learning is modeled as a Markov Decision Process (MDP):

An Environment E and agent states S  
A set of actions A taken by the agent  
P(s,s’)=>P(st+1=s’|st=s,at=a) is the transition probability from one state s to s’  
R(s,s’) – Immediate reward for any action  

## How can we predict stock market prices using reinforcement learning?  
The concept of reinforcement learning can be applied to the stock price prediction for a specific stock as it uses the same fundamentals of requiring 
lesser historical data, working in an agent-based system to predict higher returns based on the current environment. 
We will see an example of stock price prediction for a certain stock by following the reinforcement learning model. 
It makes use of the concept of Q learning explained further.

## Steps for designing a reinforcement learning model is –

Importing Libraries  
Create the agent who will make all decisions  
Define basic functions for formatting the values, sigmoid function, reading the data file, etc  
Train the agent  
Evaluate the agent performance  
Define the Reinforcement Learning Environment  

### MDP for Stock Price Prediction:

Agent – An Agent A that works in Environment E  
Action – Buy/Sell/Hold  
States – Data values  
Rewards – Profit / Loss  
 
### The Role of Q – Learning

Q-learning is a model-free reinforcement learning algorithm to learn the quality of actions telling an agent what action to take under what circumstances. 
Q-learning finds an optimal policy in the sense of maximizing the expected value of the total reward over any successive steps, starting from the current state.
