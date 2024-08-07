---
title: "Learning Conditional Preference Networks: an Approach Based on the Minimum Description Length Principle"
collection: talks
type: "Talk"
venue: "IJCAI 2024, the 33rd International Joint Conference on Artificial Intelligence"
date: 2024-08-08
location: "Jeju, Korea"
---

CP-nets are a very expressive graphical model for representing preferences over combinatorial spaces. They are particularly well suited for settings where an important task is to compute the optimal completion of some partially specified alternative; this is, for instance, the case of interactive configurators, where preferences can be used at every step of the interaction to guide the decision maker towards a satisfactory configuration. Learning CP-nets is challenging when the input data has the form of pairwise comparisons between alternatives. Furthermore, this type of preference data is not commonly stored: it can be elicited but this puts an additional burden on the decision maker. In this article, we propose a new method for learning CP-nets from sales history, a kind of data readily available in many e-commerce applications. The approach is based on the minimum description length (MDL) principle. We show some theoretical properties of this learning task, namely its sample complexity and its NP-completeness, and we experiment with this learning algorithm in a recommendation setting with real sales history from a car maker. [Slides](https://pfgimenez.fr/files/ijcai.pdf) - [Poster] (https://pfgimenez.fr/files/ijcai_poster.pdf)
