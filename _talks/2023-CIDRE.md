---
title: "Certifiably robust malware detectors by design"
collection: talks
type: "Talk"
venue: "CIDRE seminar"
date: 2023-06-01
location: "Ploërmel, France"
---

Malware analysis consists in analyzing suspicious software to detect malicious payload. Static malware analysis, which does not require software execution, relies increasingly on machine learning techniques to achieve scalability. Although such techniques obtain very high detection accuracy, they can be easily evaded with adversarial examples where a few modifications of the sample can dupe the detector without modifying the behavior of the software. Unlike other domains, such as computer vision, creating an adversarial example for malware without altering its functionality requires specific transformations. This article proposes a taxonomy of the transformations an attacker can use depending on the threat models that modelize their capability. We show the effectiveness of this taxonomy by proposing a new set of features and model architecture that can lead to certifiably robust malware detection by design. In addition, we show that every robust detector can be decomposed into a specific structure, which can be applied to learn empirically robust malware detectors, even on fragile features. We compare and validate these approaches with various machine-learning-based malware detection methods, allowing for robust detection with minimal detection performance reduction.
