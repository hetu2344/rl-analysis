# Q-Learning and Deep Q-Learning Research Project

## Abstract
This research project delves into the fundamentals of reinforcement learning, focusing on two key algorithms: Q-Learning and Deep Q-Learning. It explores how an agent can learn through interactions within a given environment by receiving rewards, emphasizing the absence of a model of the environment in Q-Learning and the integration of deep learning in Deep Q-Learning to manage complex scenarios with extensive states and actions.

## Introduction
Reinforcement learning involves learning through interactions with an environment and observing the rewards from these interactions. This project begins with a discussion of core concepts such as policies, value functions, and Markov Decision Processes (MDPs), before progressing into the specifics of Q-Learning and Deep Q-Learning.

## Project Structure
- `src/`: Contains all _LaTeX_ source code used for compiling to pdf.
- `docs/images`: Contains al of the images used.
- `Research Paper`: The final research paper.

## Algorithms Overview
### Q-Learning
Q-Learning is a model-free algorithm in reinforcement learning that does not require a model of the environment and helps the agent to learn the optimal policy by using a Q-value function.

### Deep Q-Learning (DQN)
Deep Q-Learning, or DQN, extends Q-Learning by using deep neural networks to approximate the Q-value function, allowing it to handle environments with large state and action spaces effectively.

## Key Concepts
- **Markov Decision Processes (MDPs):** Framework for modeling decision making where outcomes are partly random and partly under the control of a decision maker.
- **Policy:** Defines the agent's way of behaving at a given time.
- **Value Function:** Estimates how good it is for the agent to be in a given state.
- **Q-Value:** Represents the expected future rewards obtained from a state-action pair, following a certain policy.
