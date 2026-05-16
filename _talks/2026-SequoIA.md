---
title: "CasinoLimit: An Offensive Dataset Labeled with MITRE ATT&CK Techniques"
collection: talks
type: "Talk"
venue: "SequoIA workshop on AI and cybersecurity"
date: 2026-06-24
location: "Rennes, France"
---

Cybersecurity exercises are a common way to train and evaluate the skills of cybersecurity professionals. These exercises also provide a unique opportunity to generate datasets with realistic attack traces on non-sensitive systems. Nevertheless, the collected logs are unlabeled, and deciding which logs are related to pentesters is a difficult problem. In this paper, we present a novel methodology to label efficiently both system and network logs using MITRE ATT&CK techniques. To demonstrate the effectiveness of our approach, we introduce CasinoLimit, a dataset generated from a pentest exercise that has been played by 114 participants where we collected 540 GB of attack data. We apply our methodology to accurately label these logs with a semi-automatic approach: labels are inferred from the shell sessions and propagated to the network sessions, and eventually corrected by a junior analyst. An expert analyst has manually reviewed all the labels that have been computed to ensure the quality of the labeling process. The results of the pentest exercise are deeply discussed. We show the variability of players' behaviors and that players can be distinguished by their command line habits. In addition, the high level of granularity of labels coupled with the number of participants enables multiple other applications. With this paper, we release the full dataset and the associated labeling tool, Manatee, which can be used to browse the logs and labels. To support the generalization of our approach, we made it possible to load other datasets with this tool.
