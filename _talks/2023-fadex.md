---
title: "Towards Understanding Alerts raised by Unsupervised Network Intrusion Detection Systems"
collection: talks
type: "Talk"
venue: "FADEx Seminar"
date: 2023-10-19
location: "Rennes, France"
---

The use of Machine Learning for anomaly detection in cyber security-critical applications, such as intrusion detection systems, has been hindered by the lack of explainability. Without understanding the reason behind anomaly alerts, it is too expensive or impossible for human analysts to verify and identify cyber-attacks. Our research addresses this challenge and focuses on unsupervised network intrusion detection, where only benign network traffic is available for training the detection model. We propose a novel post-hoc explanation method, called AE-pvalues, which is based on the p-values of the reconstruction errors produced by an Auto-Encoder-based anomaly detection method. Our work identifies the most informative network traffic features associated with an anomaly alert, providing interpretations for the generated alerts. We conduct an empirical study using a large-scale network intrusion dataset, CICIDS2017, to compare the proposed AE-pvalues method with two state-of-the-art baselines applied in the unsupervised anomaly detection task. Our experimental results show that the AE-pvalues method accurately identifies abnormal influential network traffic features. Furthermore, our study demonstrates that the explanation outputs can help identify different types of network attacks in the detected anomalies, enabling human security analysts to understand the root cause of the anomalies and take prompt action to strengthen security measures. [Slides](https://pfgimenez.fr/files/fadex.pdf)
