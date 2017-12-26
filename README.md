# combinatorial optimization with DL/RL: IPython tutorials
This tutorial demonstrates technique to solve combinatorial optimization problems such as the well-known travelling salesman problem. The method was presented in the paper [Neural Combinatorial Optimization with Reinforcement Learning](https://arxiv.org/abs/1611.09940).

The Algorithm applies the pointer network architecture wherein an attention mechanism is fashioned to point to elements of an input sequence, allowing a decoder to output said elements. The network is trained by reinforcement learning using an actor-critic method. 

**Note!** This model does not beat existing baselines for TSP, moreover local search method LK-H solves these tsp tasks to optimality in seconds on a CPU, compared to suboptimal results by this model in several hours on a GPU. 

The algorithm consists of two parts:

## Pointer Network

Intro to PN for simple sorting task: [Intro to Pointer Network.ipynb](https://github.com/higgsfield/np-hard-deep-reinforcement-learning/blob/master/Intro%20to%20Pointer%20Network.ipynb).

Paper: [Pointer Networks](https://arxiv.org/abs/1506.03134).

Blog post by fast ml: [Introduction to pointer networks](http://fastml.com/introduction-to-pointer-networks/).

## Neural Combinatorial Optimization

[Neural Combinatorial Optimization.ipynb](https://github.com/higgsfield/np-hard-deep-reinforcement-learning/blob/master/Neural%20Combinatorial%20Optimization.ipynb) 

Paper: [Neural Combinatorial Optimization with Reinforcement Learning](https://arxiv.org/abs/1611.09940)


