![GitHub repo size](https://img.shields.io/github/repo-size/alimirash/AI_HW_Iris_Clustring)
![GitHub contributors](https://img.shields.io/github/contributors/alimirash/AI_HW_Iris_Clustring)
![GitHub stars](https://img.shields.io/github/stars/alimirash/AI_HW_Iris_Clustring?style=social)
![GitHub forks](https://img.shields.io/github/forks/alimirash/AI_HW_Iris_Clustring?style=social)


# Iris Flower Clustering using Genetic Algorithm

This notebook demonstrates how to use a genetic algorithm to find an optimal clustering configuration for the Iris flower dataset. 

## Overview

The Iris dataset contains measurements of sepal length, sepal width, petal length, and petal width for 150 Iris flowers spanning 3 species (Setosa, Versicolor, Virginica).

The goal is to cluster the flowers into 3 clusters representing the 3 species, without using the actual species labels. 

Genetic algorithms are search heuristics that mimic natural selection to find optimal solutions to problems. We use a genetic algorithm here to evolve a population of clustering configurations, selecting the fittest to produce better subsequent generations.

## Contents

The notebook contains the following key sections:

- Imports and data loading
- Population initialization 
- Mutation and crossover functions
- Objective function to calculate fitness
- Main genetic algorithm function
- Running the algorithm and printing the best solution

The genetic algorithm evolves a population of cluster assignments over multiple generations. Mutation and crossover produce variations. The fitness is based on the Within-Cluster Sum of Squares, which the algorithm minimizes.

The final evolved clustering configuration accurately separates the flowers into the 3 species clusters.

## Usage

To use the notebook:

1. Run all cells in order
2. Modify hyperparameters like population size, number of generations, and mutation rate to tweak performance
3. Visualize clusters and compare to actual species to evaluate accuracy

The genetic algorithm approach can be applied to clustering other datasets as well.

## References

The Iris dataset is a classic machine learning dataset, originally published by Fisher (1936).

This notebook is based on genetic algorithm concepts from places like:

- Goldberg and Holland, Genetic Algorithms and Machine Learning
- Mitchell, An Introduction to Genetic Algorithms
