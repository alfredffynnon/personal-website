---
title: "Simplexes and Population Stability"
description: "How the state of an evolving population becomes a point in a simplex, and what it means for that point, and a strategy, to be stable."
date: 2026-06-20
---

If we suppose that there are only two types of individuals within a population, defectors and cooperators, then the fraction of cooperators can be represented as _x_ and the fraction of defectors as _1 − x_. In this sense, the entire state of the population can be captured using the single variable _x_. The space of all possible population configurations is a line segment between 0 and 1. This line segment is known as a 1-simplex. The simplex is the simplest shape that represents the set of possible configurations of the population. A population with three types of individuals would form a triangle, a 2-simplex. With _n_ types of individuals within a given population, there is an _(n − 1)_-dimensional simplex. The process of evolution changes the point within a given simplex over time. Both the Fisher-Wright and Moran processes are ways of modelling the movement of the point within the simplex over generations.

Population stability relates to the different ways that a point within a simplex can remain stable. An equilibrium is a point where the population does not change, but stability has to do with whether a point will return to equilibrium if moved slightly. A population is considered stable if a small group of mutants cannot invade it. A strategy that results in population stability is known as an evolutionarily stable strategy (ESS): when everyone plays this strategy, the population cannot be invaded by a small group of mutants.
