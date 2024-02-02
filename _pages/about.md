---
permalink: /
title: "Hi!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an associate professor at [CentraleSupélec](https://www.centralesupelec.fr/) (Rennes, France) in the PIRAT research team (ex-[CIDRE](https://team.inria.fr/cidre/)). I work mostly on intrusion detection systems (IDS), and on how to make them more reliable, more usable, and more assessable:
- by designing new XAI tools to explain behavioral, semi-supervised IDS
- by proposing new representations of cybersecurity data (network communications, malware dynamic analysis, etc.)
- by devising new techniques of synthetic network traffic generation based on explainable AI and data mining

**I am hiring!**
- Post-doctoral position on white-box and black-box web application fuzzing based on formal grammars (part of the REV project, with LAAS-CNRS)
- PhD position on transfer learning for network data generation (with DGA, Télécom SudParis and Inria)

# Ongoing collaborations

## Inria’s Principal Investigator of [SecGen](https://files.inria.fr/secgen) (2023-2025)

SecGen is an associated team ("Équipe Associée") between Inria and CISPA (Saarbrücken, Germany). Security datasets are essential for research, but their quality is disputed: age, lack of diversity, human errors, etc. We propose to generate synthetic data to alleviate such issues. We plan to use data mining to generate network traces with proper temporal dependencies to generate more faithful data with less training data. This dataset will be evaluated with the performances of a network intrusion detection system.

## [Superviz](https://files.inria.fr/superviz/) (2022-2028)

Superviz is a project of the [PEPR Cybersécurité](https://www.pepr-cybersecurite.fr/). It addresses the following challenges: (i) the increase in the number and diversity of objects, (ii) the complexity of interconnected systems, (iii) the existence of increasingly complex and silent targeted attacks, and (iv) the treatment of massive attacks which rapidly affect a significant number of victims.

## REV (2023-2028)

REV is a project of the PEPR Cybersécurité. It addresses the following challenges: (i) holistic vulnerability analysis, from hardware to software to communications, (ii) characterization and understanding of the degrees of exploitation and the ability to circumvent modern protections, and (iii) vulnerability analysis's legal aspects (ethical issues, fairness of digital evidence).

## Other collaborations

I regularly work with researchers from:
- DGA-MI (Bruz) on intrusion detection
- Institut Mines-Télécom (Palaiseau) on data generation
- IRIT (Toulouse) on machine learning
- LAAS-CNRS (Toulouse) on formal language theory applied to security

# Recent publications
  {% assign counter = 0 %}
  <ul>{% for post in site.publications reversed %}
    {% if counter < 5 %}
      {% include archive-single-cv.html %}
      {% assign counter = counter | plus: 1 %}
    {% endif %}
  {% endfor %}</ul>

# Contact

Bureau 506  
CentraleSupélec – Campus de Rennes  
Avenue de la Boulaie  
35510 Cesson-Sévigné – France  
[pierre-francois.gimenez@centralesupelec.fr](mailto:pierre-francois.gimenez@centralesupelec.fr)
