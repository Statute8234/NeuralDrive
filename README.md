# NeuralDrive

The project simulates autonomous cars navigating a maze-like environment using neural networks trained using a genetic algorithm. The cars are represented by sprites with radars, and can move forward or backward. The simulation environment is rectangular with green obstacles, and collisions are removed. The project showcases how neural networks and genetic algorithms can be used to train autonomous vehicles.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Imports](#Imports)
- [Rating: 5/10](#Rating)

# About

The project simulates autonomous cars navigating through a maze-like environment using neural networks trained using a genetic algorithm and the NEAT framework. The cars aim to avoid collisions with obstacles while maximizing distance traveled. Each car is represented by a sprite on the screen and equipped with radars to detect obstacles. The neural networks receive input from the cars' radars and output commands to control their movement. The simulation environment is a rectangular area with green rectangles representing obstacles. If a car collides with an obstacle, it is removed from the simulation. The project showcases how neural networks and genetic algorithms can be used to train autonomous vehicles in complex environments.

# Features

The autonomous car simulation project simulates self-driving cars navigating through a maze-like environment, using neural networks and genetic algorithms. The project aims to evolve these networks to perform well in the given environment. Cars aim to avoid collisions with obstacles while maximizing distance traveled within the maze. Car representation and sensing involve sprites on the screen representing each car and radars detecting obstacles, which provide input to the neural networks. The simulation environment is a rectangular area resembling a maze, with green rectangles representing obstacles. If a car collides with an obstacle, it is removed from the simulation. The project showcases how neural networks and genetic algorithms can train autonomous vehicles, highlighting the complexity of real-world environments and the need for adaptive learning. Overall, this simulation project provides insights into the field of autonomous vehicle development and the role of AI techniques in training them.

# Imports

pygame, os, math, sys, neat, random

# Rating

For its functionality, integration of Pygame, and NEAT implementation. It implements a simulation of cars navigating through an environment using a simple neural network and genetic algorithm. However, there are areas for improvement, such as code organization, variable naming, and error handling.
The code lacks proper organization and separation of concerns, which could be improved by breaking it down into smaller, more manageable functions and classes. Variable names should be clearer and more descriptive, and magic numbers should be replaced with named constants or variables with descriptive names.
Error handling mechanisms should be added for file operations, Pygame initialization, and other critical sections to make the code more robust and resilient to unexpected issues. Additional comments and documentation could be beneficial for complex sections or algorithms like NEAT.
Optimization is needed, especially in the rendering loop, to ensure smooth performance, especially as the number of cars and complexity of the environment increase. The user interface could be improved to provide better feedback and provide configurable options for file paths.
By addressing these areas, the code can be enhanced in readability, maintainability, and performance.
