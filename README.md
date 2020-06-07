# Project 2: Continuous Control - Reacher Arm
This project is part of Udacity Deep Reinforcement Learning Nanodegree.

## Project Details
In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of the agent is to maintain its position at the target location for as many time steps as possible.

![image](env.gif)

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

The goal of the project is to train 20 identical agents in the environment to get an average score of +30 (over 100 consecutive episodes, and over all agents).

## Getting Started
The project has dependency on following libraries:

* Python 3
* PyTorch
* UnityEnvironment
* Matplotlib
* Numpy

## Instructions
The project has Continuous Control (Jupyter) Notebook as the base file. 

The environment class is called in the notebook to show the state and action spaces. The ddpg() function is defined in the notebook which calls the agent class defined in ddpg_agent.py to take actions and to learn from traversed states. 

The actor and critic neural network models are defined in model.py which are called by the learning function (Agent.step).

Project report discusses the learning algorithm and results.
