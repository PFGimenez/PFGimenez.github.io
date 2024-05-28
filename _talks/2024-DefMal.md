---
title: "Robust malware detectors by design"
collection: talks
type: "Talk"
venue: "DefMal annual workshop"
date: 2024-06-03
location: "Saint-Malo, France"
---

This work present the cooperation with CISPA on robust malware detectors. Malware analysis involves analyzing suspicious software to detect malicious payload. Static malware analysis, which does not require software execution, relies increasingly on machine learning techniques to achieve scalability. Although such techniques obtain very high detection accuracy, they can be easily evaded with adversarial examples where a few modifications of the sample can dupe the detector without modifying the behavior of the software. Unlike other domains, such as computer vision, creating an adversarial example for malware without altering its functionality requires specific transformations. We propose a taxonomy of the transformations an attacker can use depending on the threat models that modelize their capability. We show the effectiveness of this taxonomy by proposing a new set of features and model architecture that can lead to certifiably robust malware detection by design. In addition, we show that every robust detector can be decomposed into a specific structure, which can be applied to learn empirically robust malware detectors, even on fragile features. Our framework ERDALT is based on this structure.
