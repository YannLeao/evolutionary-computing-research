# What Is an Evolutionary Algorithm?

**Source:** Introduction to Evolutionary Computing — Eiben & Smith  
**Chapter:** 3 — What Is an Evolutionary Algorithm?

## Overview

This chapter introduces the fundamental structure of evolutionary algorithms and their main components.  
It explains how populations of candidate solutions evolve over time through variation and selection, balancing exploration and exploitation.  
It also highlights important properties such as probabilistic selection and [[anytime-behaviour]].

## Key Concepts
- [[evolutionary-algorithm]]
- [[components-of-ea]]
- [[description-ea]]
- [[exploration-vs-exploitation]]
- [[anytime-behaviour]]

##  Main Ideas

### Active Forces  
  
There are two main forces that drive evolutionary algorithms:  
  
1. **Variation operators** ([[mutation]] and [[recombination-or-crossover]]) introduce diversity into the population.  
2. **Selection** acts as a pressure that increases the average fitness of the population.
### Dialect Differences  
  
Different evolutionary computing paradigms (or "dialects") are mainly distinguished by how candidate solutions are represented.  
  
This representation affects how variation operators ([[mutation]] and [[recombination-or-crossover]]) operate, but it does **not fundamentally change the role of selection**.
  
### Probabilistic Selection Mechanism  
  
Parent selection (and survival selection) is typically probabilistic.

Even low-quality individuals are often given a small **but non-zero probability** of being selected.  
This helps prevent the search from becoming too greedy and reduces the risk of getting stuck in a **local optimum**.
### Initialization and Runtime Behaviour  
  
In many cases, evolutionary algorithms show rapid improvements early in the search process, making careful initialization less critical.  
  
![[Pasted image 20260321220234.png]]  
  
Additionally, due to their [[anytime-behavior]], evolutionary algorithms can return progressively better solutions over time.  
  
However, after a certain point , additional computational effort often leads to diminishing improvements in solution quality.


