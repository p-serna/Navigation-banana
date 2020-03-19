# Navigation-banana

## About

This is a repository for a navigation task, picking up bananas in a Unity enviroment. It uses a [rainbow agent](https://arxiv.org/abs/1710.02298) to solve the problem. It is considered as solved when it reaches score 13, and this agent reaches score 15 in less than 700 episodes.

The environment consists in picking up normal bananas in a 2d plane, avoiding blue bananas. We provide to the agent a 37 dimensional state (floating numbers), and the dimension of the action space is 4 (left, right, up and down). 

## For review

- File Report.md 

- File model.py includes the Duel Q Network

- File dqn_agent.py includes 4 classes, 2 basic classes of Agent and ReplayBuffer, and 2 specialized  subclasses AgentRainbow and ReplayBufferPrioritized that improves on the previous two to implement the Rainbow agent.

- Navigation.ipynb guides through the training of the Rainbow agent



## Getting Started

In the jupyter notebook [Navigation.ipynb](Navigation.ipynb) we guide through the training of a Rainbow agent in the described scenario.

## Requirements

- Numpy
- Matplotlib
- Pytorch
- Unity Environment
- requirements.txt in python folder (it can be installed from jupyter notebook)
