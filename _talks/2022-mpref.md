---
title: "The complexity of unsupervised learning of lexicographic preferences"
collection: talks
type: "Talk"
venue: "M-PREF Workshop of IJCAI"
date: 2022-07-23
location: "Vienne, Autriche"
---

This work considers the task of learning users’ preferences on a combinatorial set of alternatives, as generally used by online configurators, for example. In many settings, only a set of selected alternatives during past interactions is available to the learner. Fargier et al. [2018] propose an approach to learn, in such a setting, a model of the users’ preferences that ranks previously chosen alternatives as high as possible; and an algorithm to learn, in this setting, a particular model of preferences: lexicographic preferences trees (LP-trees). In this paper, we study complexity-theoretical problems related to this approach. We give an upper bound on the sample complexity of learning an LP-tree, which is logarithmic in the number of attributes. We also prove that computing the LP tree that minimises the empirical risk can be done in polynomial time when restricted to the class of linear LP-trees. [Slides](https://pfgimenez.github.io/files/mpref.pdf)
