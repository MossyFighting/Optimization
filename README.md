# Genetic Algorithm
# 1. Introduction
Genetic algorithm (GA) is a heuristic search that is based on the idea of natural evolution in order to give the solution to some very complicated problems in reality ranging from Engineering, Economics, and so on. The main part of GA is a process of natural selection where some of individuals in the population are selected for producing their children in next generation. 

In general, the GA is deployed when we do not know how the solution looks like. For example, if we want to build a house with some predefined goals such as minimum cost for building, usage of cheap material but still good quality, as much rooms as possible, and so on. Fortnately, the GA will let us know the the best possible house that one will have after going through tremendously all possible aspects of demands but with relatively acceptable time.

# 2. Natural Selection
Natural environment is witnessing a rule in which eventually the strongest one will survive while the weak one will be eliminated. The GA is based on the natural selection uses the same theory to remove the weak ones (e. g., characters, traits, genes, ...) while keep the best solution. 

The GA is strongly inspired by the natural selection that are depicted in the following figures. The figure is a closed-loop, starting from a population with several individuals, then among them, some are selected based on some criteria (e. g., scores, ...) and used for reproduction. 

<p align="center">
  <img  width="600" height="200" src="https://github.com/MossyFighting/Optimization/blob/master/images/GA_general.png" />
</p>

The reproduction process is comprised of many steps, selected pair (or many pairs) interact(s) with each other, producing some offsprings by using some methods (i.g., crossover), mutate some genes with hope to create superb genes if possible (i. g., flip gene if some conditions are satisfied), and reassure only mixed traits of those pairs actually better than pair(s) themself by comparision them with their mixed genes. 

Finally, the population is updated by adding some new and superb gene or still keep the old ones if the new one is not as expected. Then the loop is continuing until some criteria are met and stop. 

Summary, the natural process can be seen as a 6-step procedure, specifically:
1. Population initialization 
2. Fitness 
3. Selection 
4. Interation (e.g., Cross-over)
5. Offsprings production (e.g., mutation)
6. Elitism and update population 

# 3. Analysis Genetic algorithm
## 3.1 Population initialization and fitness

<p align="center">
  <img   src="https://github.com/MossyFighting/Optimization/blob/master/images/Population_fitness.png" />
</p>

## 3.2 Fitness

<p align="center">
  <img   src="https://github.com/MossyFighting/Optimization/blob/master/images/fitness.png" />
</p>

## 3.3 Selection

<p align="center">
  <img   src="https://github.com/MossyFighting/Optimization/blob/master/images/Crossover.png" />
</p>

## 3.4 Crossover

<p align="center">
  <img   src="https://github.com/MossyFighting/Optimization/blob/master/images/Mutation.png" />
</p>

## 3.5 Mutation

## 3.6 Elitism and update population

# 4. Verification Example

<p align="center">
  <img   src="https://github.com/MossyFighting/Optimization/blob/master/images/run_example.png" />
</p>
