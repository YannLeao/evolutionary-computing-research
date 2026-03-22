# Fitness Function

## Definition
The role of the evaluation function is to represent the requirements the population should adapt to meet. It forms the basis for selection, and so it facilitates improvements.

Typically, this function is composed from the inverse representation (to create the corresponding phenotype) followed by a quality measure in the [[phenotype-space]].
## Example
if the task is to find an integer x that maximises $x^2$ , the fitness of the genotype 10010 could be defined by decoding its corresponding phenotype (10010 → 18) and then taking its square: $18^2$ = 324.

## In Context
Where this appears:
-[[eiben-smith-ch03-evolutionary.md]]
