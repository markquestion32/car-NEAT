This project utilizes the NEAT (NeuroEvolution of Augmenting Topologies) algorithm to evolve neural networks capable of autonomously controlling cars in a simulation environment. The goal is to evolve neural networks that can effectively navigate complex environments, avoid obstacles, and reach designated targets.

Key Components:

Car Simulation: The simulation environment consists of cars placed within a defined space, each controlled by a neural network. Cars interact with obstacles and boundaries while attempting to navigate toward a goal.

NEAT Algorithm: NEAT is employed to evolve neural networks over multiple generations. Genetic operators such as mutation and crossover are applied to create new generations of networks with improved performance.

Neural Network Design: Neural network architectures are defined by parameters specified in a configuration file. Input data from the car's sensors is processed to produce output representing the car's actions.

Fitness Evaluation: The fitness of each neural network is evaluated based on the performance of the car it controls in the simulation. Evaluation criteria include factors such as distance traveled, time taken, and avoidance of obstacles.

Project Goals:

Primary Goal: Evolve neural networks capable of autonomously controlling cars to navigate the simulation environment effectively.
Secondary Goals: Optimize performance metrics such as speed, efficiency, and robustness of car navigation.
Expected Outcomes:

The project aims to produce neural networks demonstrating adaptive behavior, effectively navigating cars through complex environments.
Evolved neural networks should exhibit improved performance over successive generations, showcasing the effectiveness of the NEAT algorithm in solving complex control problems.
