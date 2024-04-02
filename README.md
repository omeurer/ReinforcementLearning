# ReinforcementLearning
Folder containing all my projects in Reinforcement Learning.


1. [Flappy Bird Game](https://github.com/omeurer/ReinforcementLearning/blob/main/FlappyBird_RL.ipynb)
   This project implements 2 agents (a Monte Carlo and Sarsa-Lambda) from scratch, using an already-implemented environment of the game Flappy Bird.
   It works very well on Notebook, even with a dynamic rendering. 

   ![](https://github.com/omeurer/ReinforcementLearning/blob/main/expected_sarsa_infinite_play.gif)
   
   
   *Spoiler : the bird flaps well.*

   2. [Stock Trading Agent](https://github.com/omeurer/ReinforcementLearning/blob/main/STOCK_PREDICTION_RL_PROJECT.ipynb) : This project implements a Deep Q Network Agent on 3 Environments. The data is the stock of Apple from 2022 to now (March 2024).
      The agent has possible 3 actions {buy, sell, hold}, and the state space increases from {current price} to {current price, volume exhanged, rolling average} to {current price, volume exhanged, rolling average, lag-1, lag-5}.
      
*Spoiler : The agent should write 'proud overfitter and portfolio's vanisher' on it's resume.*
