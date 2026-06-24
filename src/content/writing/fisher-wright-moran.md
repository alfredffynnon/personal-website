---
title: "The Fisher-Wright and Moran Processes"
description: "Two models of how cooperators and defectors rise and fall in a finite population, one replacing every individual at once, the other one individual at a time."
date: 2026-06-13
---

We can begin by conceptualising a population of size _N_. Within the population, there are two types of individuals: cooperators, denoted _c_, and defectors, denoted _d_. The number of cooperators at any given time can be represented by _i_, while the number of defectors is necessarily _N − i_. The question in evolution is what happens to _i_ over time. The Fisher-Wright process and the Moran process are useful models to help answer this question.

A central concept to both processes is fitness. Fitness can be understood as reproductive ability, such that an individual with higher fitness is more likely to produce offspring. Let the fitness of cooperators be _Fc_ and the fitness of defectors be _Fd_. Within evolutionary game theory, fitness is derived from the payoffs. Both cooperators and defectors receive some average payoff from interacting with others, which translates into their respective likelihoods of reproducing successfully.

The Fisher-Wright process models the evolution of the population as one generation being entirely replaced by another. At a given time _t_, there are _N_ individuals. At _t + 1_, there are _N_ individuals who are the direct offspring of the previous _N_. A new generation replaces the previous one in discrete steps. Considering that there are _i_ cooperators and _N − i_ defectors, along with our definition of fitness, we can look at how the population evolves. The total reproductive weight of the cooperators is `i · Fc`, while that of the defectors is `(N − i) · Fd`. The probability _p_ that any one offspring is a cooperator is the ratio of the reproductive weight of cooperators to the total reproductive weight of the population:

`p = (i · Fc) / ( i · Fc + (N − i) · Fd )`

The probability that any one offspring is a defector is simply _1 − p_. Therefore, if the number of cooperators and defectors at time _t_ is _i_ and _N − i_, then the expected numbers at time _t + 1_ will be `N · p` and `N · (1 − p)` respectively.

Unlike the Fisher-Wright process, in which the entire population is replaced each time, the Moran process changes the population one individual at a time. At each step, one individual is born and one dies, so that the population _N_ remains constant. As before, the number of cooperators is _i_ and the number of defectors is _N − i_, and the probability that the reproducing individual is a cooperator is the same `p` as above, while the probability that it is a defector is _1 − p_. The individual that dies is chosen uniformly at random, so the probabilities that it is a cooperator or a defector are _i / N_ and _(N − i) / N_ respectively. There are three possibilities: a cooperator reproduces and a defector dies, which increases the number of cooperators by one; a defector reproduces and a cooperator dies, which decreases it by one; or a cooperator reproduces and a cooperator dies, or a defector reproduces and a defector dies, resulting in no change.

Both the Fisher-Wright process and the Moran process serve as mathematical models for finite-population evolution over multiple generations.
