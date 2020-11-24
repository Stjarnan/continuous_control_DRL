[image1]: https://user-images.githubusercontent.com/10624937/43851024-320ba930-9aff-11e8-8493-ee547c6af349.gif "Trained Agent"
# continuous_control_DRL
 Deep Reinforcement Learning model for the Reacher environment

### Introduction

![Trained Agent][image1]

Implement a DDPQ agent acting in the [Reacher](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher) environment. The agent controls a double-jointed arm with the goal of keeping it inside of a moving target location.


- This version contains 20 identical agents, all learning together. This is considered solved when the agents get an average score of +30 (over 100 consecutive episodes, and over all agents).

The mechanics of this environment:

- *Rewards*: +0.1 for each timestep where the agent's hand is in the goal location.
- *State space*: 33 variables per agent (includes position, rotation, velocity, and angular velocities of the arm)
- *Action space*: Vector of 4 numbers, corresponding to torque applicable to two joints. Each value in this vector should be between -1 and 1.

### Getting Started

1. Download the environment from one of the links below.  You only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)


2. Place the environment in the project folder

### Instructions

Follow the instructions in `Continuous_Control.ipynb` to get started with training your own agent and then enjoy watching it improve!  


