# NeuralDrive

The project simulates autonomous cars navigating a maze-like environment using neural networks trained using a genetic algorithm. The cars are represented by sprites with radars, and can move forward or backward. The simulation environment is rectangular with green obstacles, and collisions are removed. The project showcases how neural networks and genetic algorithms can be used to train autonomous vehicles.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Imports](#Imports)
- [Rating: 7/10](#Rating)

# About

The project simulates autonomous cars navigating through a maze-like environment using neural networks trained using a genetic algorithm and the NEAT framework. The cars aim to avoid collisions with obstacles while maximizing distance traveled. Each car is represented by a sprite on the screen and equipped with radars to detect obstacles. The neural networks receive input from the cars' radars and output commands to control their movement. The simulation environment is a rectangular area with green rectangles representing obstacles. If a car collides with an obstacle, it is removed from the simulation. The project showcases how neural networks and genetic algorithms can be used to train autonomous vehicles in complex environments.

# Features

The autonomous car simulation project simulates self-driving cars navigating through a maze-like environment, using neural networks and genetic algorithms. The project aims to evolve these networks to perform well in the given environment. Cars aim to avoid collisions with obstacles while maximizing distance traveled within the maze. Car representation and sensing involve sprites on the screen representing each car and radars detecting obstacles, which provide input to the neural networks. The simulation environment is a rectangular area resembling a maze, with green rectangles representing obstacles. If a car collides with an obstacle, it is removed from the simulation. The project showcases how neural networks and genetic algorithms can train autonomous vehicles, highlighting the complexity of real-world environments and the need for adaptive learning. Overall, this simulation project provides insights into the field of autonomous vehicle development and the role of AI techniques in training them.

# Imports

pygame, os, math, sys, neat, random

# Rating

The concept of simulating autonomous cars in a maze-like environment is intriguing and relevant to artificial intelligence and robotics research. The NEAT framework for training neural networks adds complexity and realism to the simulation. Visual representation of cars and obstacles provides an intuitive understanding. However, the simulation lacks interactivity, limited complexity, and dependence on external files. Adding more complex obstacles or dynamic elements could enhance the challenge and realism. The project also relies on external files for configuration and image loading, making it less portable and harder to modify for users unfamiliar with the file structure.
