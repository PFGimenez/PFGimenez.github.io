---
permalink: /
title: "Hello there!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an associate professor at [CentraleSupélec](https://www.centralesupelec.fr/) (Rennes, France) in the [CIDRE](https://team.inria.fr/cidre/) research team. I have various areas of interest, most notably:
- applying machine learning techniques to security problems, such as malware analysis, anomaly detection, and data generation
- the application of formal languages theory on system and protocol security, especially on injection-based vulnerabilities

# Ongoing collaborations

## [Superviz](https://files.inria.fr/superviz/) (2022-2028)

Superviz is a project of the PEPR Cybersécurité. It addresses the following challenges: (i) the increase in the number and diversity of objects to be supervised, (ii) the complexity of systems interconnected to form large critical infrastructures on a European scale, (iii) the existence of increasingly complex and silent targeted attacks, and (iv) the treatment of massive attacks which rapidly affect a significant number of victims. Faced with these challenges, it is necessary to significantly improve the efficiency of the detection-reaction chain (response and remediation). The project's main objective is to provide new solutions and advance the current scientific state of the art.

## DefMal (2022-2028)

DefMal is a project of the PEPR Cybersécurité. The objective of the project is to improve the knowledge and understanding of malicious programs and to develop countermeasures. The project involves the human and social sciences, as in the majority of computer attacks, humans are implicated as the "weak link". Today, malicious programs are increasingly sophisticated and manage to hide themselves and what they are doing. We need to find new techniques to analyze these programs and understand how they operate.

## [SecGen](https://files.inria.fr/secgen) (2023-2025)

SecGen is an associated team ("Équipe Associée") between Inria and CISPA (Saarbrücken, Germany). Security datasets are essential for research, but their quality is disputed: age, lack of diversity, human errors, etc. We propose to generate synthetic data to alleviate such issues. We plan to use data mining to generate network traces with proper temporal dependencies to generate more faithful data with less training data. This dataset will be evaluated with the performances of a network intrusion detection system. I am Inria’s PI (principal investigator) for this project.

## Other collaborations

I regularly work with researchers from:
- DGA (Bruz) on intrusion detection
- Institut Mines-Télécom (Palaiseau) on intrusion detection and data generation
- IRIT (Toulouse) on data mining
- LAAS-CNRS (Toulouse) on formal language theory applied to security
- NICT (Tokyo, Japan) on XAI for security

# Some recent publications
  <ul>{% for post in site.publications limit:5 %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

# Contact

Bureau 506  
CentraleSupélec – Campus de Rennes  
Avenue de la Boulaie  
35510 Cesson-Sévigné – France  
[pierre-francois.gimenez@centralesupelec.fr](mailto:pierre-francois.gimenez@centralesupelec.fr)
