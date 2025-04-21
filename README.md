# Autonomous Driving - Reinforcement-Learning Project

**Reinforcement learning** (RL) is a type of machine learning process that focuses on decision making by autonomous agents. An autonomous agent is any system that can make decisions and act in response to its environment independent of direct instruction by a human user. In reinforcement learning, an autonomous agent learns to perform a task by trial and error in the absence of any guidance from a human user.

**Autonomous Driving** has long been considered a field in which Reinforcement algorithms excel.This project aims to leverage the power of RL to create an intelligent agent that can solve the Farama’s foundation “highway-env” project, namely the **Highway environment** (refer to https://highway-env.farama.org/environments/highway/ )

A preview of the environment:

![Demo](https://github.com/Gl-ferreira/Autonomous-Driving-Reinforcement-Learning-Project/blob/main/highway%20environment%20gif.gif?raw=true)

To fulfill this project, was necessary to complete the following requirements:

- Use only 2 of the existing **environment's observation format** (Kinematics, Grayscale Image, Occupancy Grid and Time to collision).
  
- Use only 2 of the possible **agents' actions** (continuous actions, discrete actions and discrete meta actions).
  
- Any algorithm is valid to use, with a minimum of **3 different algorithms.**
  
- Respect the **environment's configuration** in the template notebook.
  
- The aforementioned criteria must be respected, and amount to **4 different solutions.**

## Solutions

The final four solutions, with respect to the project requirements were:

| Solution   | Model              | Observation Space | Action Space           |
|------------|-------------------|-------------------|------------------------|
| Solution 1 | SARSA              | Kinematics        | DiscreteMetaAction     |
| Solution 2 | PPO   (Proximal Policy Optimization)             | Kinematics        | DiscreteMetaAction     |
| Solution 3 | Deep Q-Network     | Kinematics        | Discrete Action        |
| Solution 4 | TD3                | Occupancy grid    | Continuous Action      |

