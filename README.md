# Space Invaders RL with DQN & DDQN
This repository contains a reinforcement learning project where **Deep Q-Network (DQN)** and **Double DQN (DDQN)** agents were trained to play **SpaceInvaders-v5** from the [Arcade Learning Environment (ALE)](https://github.com/mgbellemare/Arcade-Learning-Environment).

The goal was to explore baseline DQN performance, integrate DDQN for stability, and compare learning curves under different hyperparameter settings.

---
## Starter Code
This project was based on starter code provided for prior RL assignments.  
Original repository: [Starter Code](https://github.com/everestso/summer25/blob/main/c166f25_02b_dqn_pong.ipynb)

It includes the base DQN implementation, environment wrappers, and helper functions.

---
## Results
Gameplay Videos:

Early policy:
<video src="https://github.com/Cd881/CSCI166Project/blob/main/early.mp4" controls width="480"></video>

Final DDQN run:
<video src="https://github.com/Cd881/CSCI166Project/blob/main/later.mp4" controls width="480"></video>

The final DDQN agent demonstrates smoother Q-value estimates, improved stability, and noticeable improvement in gameplay compared to the baseline settings.
