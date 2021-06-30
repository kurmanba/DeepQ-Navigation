# Project 1: Navigation
### Introduction

In this project agent was trained to navigate and collect bananas 
in Unity environment. A reward of +1 (point) is awarded for collecting a 
yellow, and a punishment of -1 is provided for collecting a blue
banana. Thus, the goal of the agent is to maximize cumulative reward
over the episodes.


The state space has 37 dimensions and contains the agent's velocity, 
along with ray-based perception of objects around agent's forward direction.
Given this information, the agent has to learn how to best select actions. 
Four discrete actions are available, corresponding to:

- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

### Instructions

Follow the instructions in report.ipynb to see how DeepQ network was 
build to train agent to select right actions that maximize reward.


### Notes:

It is not clear for me, if some of the libraries provided in udacity are
outdated or due to other reasons I couldn't manage to run the program in 
my computer and trained the agents in udacity workspace. 