# GeneticAlgorithm

# This code implements an optimization metaheuristic to find the value of x that maximizes an objective function. The technique used is refered to as a genetic algorithm. The algorithm starts with a set of initial candidate solutions and allows them to mutate by a process that resemebles natural selection. Solutions "breed" and the "fittest" ones are retained for further breeding.

# In this problem, the solution we are searching for is a single number that maximizes an equation. The number is converted to a binary string and each digit is modeled as a genetic trait. When two solutions "mate" the offspring is dervived by selecting all traits that each parent has in common, and then randomly choosing traits where they parent traits differ. Furthermore, this child then goes through a probabilistic mutation in which any trait has a small chance of changing.

# The output is verbose to illustrate the mating and mutations at each stage of the process. 
