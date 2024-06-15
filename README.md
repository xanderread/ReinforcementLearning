# Reinforcement Learning Bipedal Walker Assignment

This assignment was for the COMP3667 Reinforcement Learning Module at Durham University. It features a reimplementation of the Symphony algorithm, enhanced with a third critic network to solve the OpenAI Gym BipedalWalker-v3 environment.

## Overview

- **Algorithm:** Modified Symphony (based on DDPG and TD3)
- **Environment:** OpenAI Gym BipedalWalker-v3
- **Performance:** Solved in 28 episodes, achieving a human-like gait
- **Enhancements:** Third critic network, fading replay buffer, Fourier series-inspired neural network architecture

## Video of Agent in Action

[Watch on YouTube](https://youtu.be/u1S0YdnwFTk)

## Abstract

This project presents a reimplementation of the Symphony algorithm to solve the BipedalWalker-v3 environment. The modified algorithm incorporates a third critic network to reduce overestimation bias, achieving faster and more stable convergence.