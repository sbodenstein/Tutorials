# Tutorials

This repository is for tutorials that I have written.

## Indaba 2019

I wrote the reinforcement learning tutorial for the [2019 Deep Learning Indaba](http://www.deeplearningindaba.com/practicals-2019.html). 

**Tutorial Philosophy**: The audience of the Indaba is very diverse both in coding ability and prior exposure to reinforcement learning. So this tutorial was designed to be interesting to a very wide audience. For beginners: solving the reinforcement learning problem using policy gradients or Q-learning can be confusing when this tutorial is the first exposure they have to the RL problem. Why not start with random search? It is both conceptually very simple, and easy to implement! This gives beginners an easy win, whilst deepening their understanding of the RL problem. Oh, and random search is of course a legitimate method: https://arxiv.org/abs/1803.07055

In addition, avoid programing complexities like inheritance (and make the code as functional as possible). For seasoned ML people: have optional sections that give deeper insight into topics I haven't seen in many other RL tutorials (eg. inspired by this paper https://arxiv.org/abs/1906.10652, I added a large section on score function estimators guided by a toy example).