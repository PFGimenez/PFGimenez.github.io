---
title: "BAGUETTE: Hunting for Evidence of Malicious Behavior in Dynamic Analysis Reports"
collection: talks
type: "Talk"
venue: "Toulouse Hacking Conference (THCon)"
date: 2024-04-04
location: "Toulouse, France"
---

Malware analysis consists of studying a sample of suspicious code to understand it and producing a representation or explanation of this code that can be used by a human expert or a clustering/classification/detection tool. The analysis can be static (only the code is studied) or dynamic (only the interaction between the code and its host during one or more executions is studied). The quality of the interpretation of a code and its later detection depends on the quality of the information contained in this representation. To date, many analyses produce voluminous reports that are difficult to handle quickly. In this article, we present BAGUETTE, a graph-based representation of the interactions of a sample and the resources offered by the host system during one execution. We explain how BAGUETTE helps automatically search for specific behaviors in a malware database and how it efficiently assists the expert in analyzing samples. We also develop a possible use case of BAGUETTE being currently researched: explainable unsupervised malware behavior clustering. [Slides](https://pfgimenez.fr/files/thcon24.pdf) - [Video](https://www.youtube.com/live/FJqWGK_SjHI?si=-bTJnVWmirAsZmCJ&t=6470)
