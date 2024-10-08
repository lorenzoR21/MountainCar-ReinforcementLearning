# MountainCar with Reinforcement Learning
This project is based on reinforcement learning. Reinforcement learning agent learns by interacting with the environment through actions, observes next state and uses observed reward for each action as feedback signal to improve policy. In this project has been implemented a Reinforcement Learning Agent based on Q-learning, which uses NN to approximate the Q-function.
In particular, in this project a DQN (Deep Q-Network) algorithm has been implemented to train an agent to reach the goal in the Mountain Car gym environment. The training performances were analyzed using the graphs of the reward and the maximum position assumed by the car. Finally, a test phase was carried out to analyze the performance of the trained model obtained in the previous training phase; the trained model was also evaluated against a random agent. Furthermore, the mountain car classic environment was modified in a new variant, in this way it was possible to evaluate the behavior and performance of the trained model (that of the classic environment).
There are two type of application:
* [Mountain Car classic](MountainCar.ipynb): The Mountain Car MDP is a deterministic MDP that consists of a car placed stochastically at the bottom of a sinusoidal valley, with the only possible actions being the accelerations that can be applied to the car in either direction. The goal of the MDP is to strategically accelerate the car to reach the goal state on top of the right hill. <img src="https://github.com/lorenzoR21/MountainCar-ReinforcementLearning/blob/main/TEST_Classic.gif">
* [Mountain Car variant](MountainCar_modLaser.ipynb): The idea of this variant remains the same as the Mountain Car, leaving the actions, rewards, goal, end condition, etc. unchanged; the addition was that of an intermittent laser. The role of this laser is as follows: when the car crosses this laser it is stopped, in particular the speed is set to 0.
 <img src="https://github.com/lorenzoR21/MountainCar-ReinforcementLearning/blob/main/TEST_Variant.gif">
 
# Implementation and Result
For the implementation details and the result see the [paper](MountainCar_paper) written by me.

## Author
[Lorenzo Russo](https://github.com/lorenzoR21)
