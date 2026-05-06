---
title: "Protocol Semantics vs. User Semantics: Predicting Cross-Domain Generalization in Intrusion Detection"
collection: talks
type: "Talk"
venue: "Superviz plenary meeting"
date: 2026-06-08
location: "Campus Cyber, Puteaux, France"
---

Machine-learning-based intrusion detection systems rarely generalize across deployment environments, often degrading when transferred to new network domains, which greatly limits their applicability to real-world settings. We hypothesize that \textit{feature category} is a key driver of cross-domain transferability in intrusion detection because L7 features (grounded in standardized protocols) are domain-invariant, while L8 features (encoding real-world action the user is performing) absorb domain-specific noise and hurt generalization. This article  introduces a novel taxonomy distinguishing lexical, syntactic, and two levels of semantic features: protocol-level (L7) and user-level (L8). To study this hypothesis, we publish Superviz26-SQL, the first four-domain SQL attack detection benchmark, and we show that feature category is a key driver of domain generalisation. Our results confirm that handcrafted Feature Extractors (FE) relying on L7 features generalize well, while FEs using L8 semantics drop by up to 8 AUROC points.  Strikingly, FEs using pretrained models (despite high in-domain AUROC scores) can collapse up to near-random performance under domain shift, and the same robustness hierarchy holds under sudden concept drift. Finally,  fine-tuning experiments show that the cross-domain gap is recoverable for most FEs with at most 10,000 target domain samples. These findings offer guidance for practitioners: L7-semantic FEs for immediate zero-shot transfer, or pretrained encoders at the cost of collecting target-domain samples and retraining.
