# Robot-Learning-NNs
Machine learning techniques for robotic with its implementations based on pytorch, scripts are from course project of MECE6616 Spring Columbia University taught by Prof. Matei Ciocarlie, all content (including files, codes and images) may not be reproduced without permission.

## Project 1
Behaviour cloning of a robot agent to get to a given goal position in a maze, a regression model is train to read both high and low dimensional data including the 2D RGB image and raw observation of the agent to estimate its current coordinate in the map, while a classification model is then used to provide the agent with the best option. The method used by classification is nearest neighbour.

## Project 2
Same circumstances for the agent as project 1, but only this time a DNN and a CNN is trained respectively for current position and raw RGB image to reach a more difficult goal as the map varies from every trail.

## Project 3
Behaviour cloning for forward dynamics of a 3 link robot arm. A teacher's arm is given to collect data when it is driven with different set of forces and durations. A DNN is then trained to recreate the data collected and used to estimate dynamic behaviour of a robot arm.

## Project 4
Similar circumstances as project3, but an MPC is implemented during both data collection and model testing rather than taking random actions.

## Project 5
Similar circumstances, but this time RL is used. Architecture of a DQN is built and trained, PPO is implemented based on Stable-Baselines3

