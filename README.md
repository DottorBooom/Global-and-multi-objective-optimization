# Global and multi objective optimization

## Index 

+ [Genetic algorithms](#genetic-algorithms)
+ [Evolution strategies](#evolution-strategies)
+ [Intro to genetic programming (pt. 1)](#intro-to-genetic-programming-(pt.-1))
+ [Intro to genetic programming (pt. 2)](#intro-to-genetic-programming-(pt.-2))
+ [Differential evolution, particle swarm optimisation and ant colony optimisation](#differential-evolution,-particle-swarm-optimisation-and-ant-colony-optimisation)
+ [Geometric semantic](#geometric-semantic)
+ [Estimation of distribution algorithms](#estimation-of-distribution-algorithms)
+ [Covariance matrix adaptation evolution strategy](#covariance-matrix-adaptation-evolution-strategy)
+ [Policy optimisation](#policy-optimisation)
+ [Distributed methods coevolution](#Distributed-methods-coevolution)
+ [Neuroevolution](#neuroevolution)
+ [Multi-objective optimization](#multi-objective-optimization)
+ [Theory of evolutionary algorithms](#theory-of-evolutionary-algorithms)
+ [Master's index](https://github.com/DottorBooom/Master-in-Data-Science-and-Artificial-Intelligence) 

## Introduction

+ It will be entirely in English, slides made by the professor on which I will take notes lesson after lesson.
+ Some books have also been recommended if you want to follow from there or go deeper, I will try to upload those as well.
+ The final exam will consist of a project assigned by the professor and an oral presentation for exposing it. The professor will ask about project's topic too.

### What you will learn

+ **Genetic alforithms**
+ **Evolution strategies**
+ **Genetic programming**
+ **Particle swarm optimization and anti-colony optimization**
+ **Differential evolution**
+ **Neuroevolutioin**
+ **EDA and CMA-ES**13_Theory_of_evolutionary-algorithm
+ **Parallel implementations**
+ **Multi-objective optimization**
+ **Coevolution**
+ **Policy optimization**
+ **Theory of evolutionary computation**

### Common rules & principles

+ Every question is **legitimate and useful**, ask what you do not understand
+ Main pourpose it to **learn**, not to grade
+ Learning is a **process**, not a result
+ Nobody is perfect or always right: **errors and mistake are natural**
+ **Learning is a process in our personal brain**, not in other's one. **Clash with your limits** before check the solution

## Genetic algorithms

Information about the course and what to expect, including recommended books. 
Examples of what this course will cover

+ Genetic algorithms: story, functioning, evolution cycle (generation, parameters, selection, crossovers and mutation), variants of GA and speial rapresentations.
+ First notebook of the course that introduce an GA algorithm with a binary string and compare the result with other algorithms (random, hill climbing and simulated annealing). It shows how does it work, how to write a propper fit and some particular case.

Slides are available [here](Lectures/1_Genetic_algorithms.pdf)

Notebook is available [here](Lectures/1_Genetic_algorithms_Ex.ipynb)

## Evolution strategies

+ Evolution strategies: the ideas, parameters and cycle, mutation and recombinations
+ Notebook that contain an implementation of an evolution strategies that try to find the optimum inside different 3Ds functions.

Slides are available [here](Lectures/2_Evolution_strategies.pdf)

Notebook is available [here](Lectures/2_Evolution_strategies_Ex.ipynb)

## Intro to genetic programming (pt. 1)

+ Genetic programmin: outlines, the evolution cycle, the rappresentations and sufficiency rule. The initialisation methods, crossover methods and mutation methods. Automatically defined functions nad what is bloat and how to solve it.
+ Notebook that show how to use an implmentation of a simbolic regression using the library gp learn. it is shown how does it work and the results.

Slides are available [here](Lectures/3_Genetic_programming.pdf)

Notebook is available [here](Lectures/3_Genetic_programming_Ex.ipynb)

## Intro to genetic programming (pt. 2)

+ Other type of GP: linear GP, what is it and motivations. Cartesian GP, what is it and encoding. Grammatical Evolution, what is it, how it works and some example.
+ Notebook implementation of linear GP for solving equations.

Slides are available [here](Lectures/4_Genetic_programming.pdf)

Notebook is available [here](Lectures/4_Linear_GP_Ex.ipynb)

## Differential evolution, particle swarm optimisation and ant colony optimisation

+ Differential evolution: what is it and how it works, mutation and crossover.
+ Particle swarm optimization: the idea, definition, the velocity components, parameters and selection of them.
+ Ant colony optimization: stigmergy in nature and the system, what is it and the cycle. How it works and how it's updated.

Slides are available [here](Lectures/5_Diff_evolution_particle_swarm_and_ant_colony.pdf)

## Geometric semantic

+ Geometric operators: the metric spaces. Geometric crossover and mutation,
+ Semantic operators: syntax vs semantics, the geometric semantic crossover and the effect on the semantics. 

Slides are available [here](Lectures/6_Geometric_semantic.pdf)

## Estimation of distribution algorithms

+ EDA: implicit and explicit models, classificataion problem, generative vs discriminative models, rejection and region-based sampling, and other methods.
+ Notebook that contains how EDA can be used to solve OneMax problem

Slides are available [here](Lectures/7_EDA.pdf)

Notebook is available [here](Lectures/7_EDA_Ex.ipynb)

## Covariance matrix adaptation evolution strategy

+ CMA-ES: what is it and how it works, sampling and rapresentation of individuals. How a cycle works, update and weights. 
+ Notebook implements CMA-ES for finding the minimum of Ackley function.

Slides are available [here](Lectures/8_CMA-ES.pdf)

Notebook is available [here](Lectures/8_CMA-ES_Ex.ipynb)

## Policy optimisation

+ Policy optimisation: types of policy, Q-learning and model-free-Q-learning. Sparse policy optimisation and the rule systems. How the rules trigger, resolve conflicts and different type of space. Pitt approach and the Samuel cycle. The ZCS algorithm and the more advanced XCS.
+ The notebook show how policy optimisation can be used to solve multiplexer problem

Slides are available [here](Lectures/9_Policy_optimization.pdf)

Notebook is available [here](Lectures/9_Policy_optimization_Ex.ipynb)

## Distributed methods coevolution

+ Parallel and distributed methods: different way to paralyze, advatage and disadvantages. Island model and all possible type of topology.
+ Coevolution: the ideas, the role of the fitness in competitive coevolution. Internal vs external fitness and different way to evaluate fitness.

Slides are available [here](Lectures/10_Distributed_methods_coevolution.pdf)

## Neuroevolution

+ Neuroevolution: quick recap on neural networks, what could be evolve. The importance of encoding, and different kind of encoding. The competing conventions problem. NEAT, CPPN  and DENSER.
+ The notebook show how a simple neural network can be evolve to solve some simple equations.

Slides are available [here](Lectures/11_Neuroevolution.pdf)

Notebook is available [here](Lectures/11_Neuroevolution_Ex.ipynb)

## Multi-objective optimization

+ Multi-objective optimization: single vs multi-objective, dominating solutions, pareto front and optimization. Non-dominated sorting, NSGA and NSGA-II, crowding distance, NSGA-III and MOPSO.

Slides are available [here](Lectures/12_Multi-objective_optimization.pdf)

## Theory of evolutionary algorithms

Slides are available [here](Lectures/13_Theory_of_evolutionary-algorithms.pdf)
