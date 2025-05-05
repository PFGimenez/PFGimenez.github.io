---
permalink: /
title: "Hi!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a research scientist at [Inria](https://www.inria.fr/) (Rennes, France) in the [PIRAT](https://team.inria.fr/pirat/) research team (ex-[CIDRE](https://team.inria.fr/cidre/)) and a member of the [LHS](https://www.lhs-rennes.fr/) laboratory at Rennes. I work mostly on intrusion detection systems (IDS), and on how to make them more reliable, more usable, and more assessable:
- by designing new XAI tools to explain behavioral, semi-supervised IDS
- by proposing new representations of cybersecurity data (network communications, malware dynamic analysis, etc.)
- by devising new techniques of synthetic network traffic generation based on explainable AI and data mining

# Future events

I am co-organizing the [ANUBIS workshop](https://superviz.inria.fr/anubis25/) at ESORICS25 on the evaluation of intrusion detection systems. Submission deadline is June 7th.

# Ongoing collaborations

## DeceptIA (2025-2027)

DeceptIA (Deception Technologies for Honeypots with Intelligence and Adaptability) is an associate team between Inria, DFKI (Germany) and Osaka Metropolitan University (Japan). It seeks to answer the following research questions: what are the characteristics of new anomalous traffic observed in large-scale honeypots deployed across multiple geolocations and services? How can we make honeypots adapt on-the-fly to the attacker's behavior and also evolve interaction between them? How can we develop an effective phishing detection system that not only accurately identifies phishing attacks, but also educates and explains the risks to end-users in a way that increases their awareness and resilience to future phishing attempts?

## [SecGen](https://files.inria.fr/secgen) (2023-2025)

I am the PI (principal invertigator) of SecGen, an associate team ("Équipe Associée") between Inria and CISPA (Saarbrücken, Germany). Security datasets are essential for research, but their quality is disputed: age, lack of diversity, human errors, etc. We propose to generate synthetic data to alleviate such issues. We plan to use data mining to generate network traces with proper temporal dependencies to generate more faithful data with less training data. This dataset will be evaluated with the performances of a network intrusion detection system.

## [REV](https://rev.s3.eurecom.fr) (2023-2028)

REV is a project of the PEPR Cybersécurité. It addresses the following challenges: (i) holistic vulnerability analysis, from hardware to software to communications, (ii) characterization and understanding of the degrees of exploitation and the ability to circumvent modern protections, and (iii) vulnerability analysis's legal aspects (ethical issues, fairness of digital evidence).

## [Superviz](https://superviz.inria.fr/) (2022-2028)

Superviz is a project of the [PEPR Cybersécurité](https://www.pepr-cybersecurite.fr/). It addresses the following challenges: (i) the increase in the number and diversity of objects, (ii) the complexity of interconnected systems, (iii) the existence of increasingly complex and silent targeted attacks, and (iv) the treatment of massive attacks which rapidly affect a significant number of victims.

## [DefMal](https://pepr-defmal.loria.fr/fr/) (2022-2028)

The DefMal project focuses on the fight against malware: a subject that affects the entire digital environment, including connected objects (IoT), embedded systems (drones), autonomous vehicles (cars), industrial systems (ICS/Scada) and, of course, the entire IT infrastructure (cloud, smartphones, firmware).

## Other collaborations

I regularly work with researchers from:
- DGA-MI and AMIAD (Bruz) on intrusion detection
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

Office F434\
Centre Inria de l'Université de Rennes\
Campus de Beaulieu, 263 Av. Général Leclerc, 35042 Rennes\
[pierre-francois.gimenez@inria.fr](mailto:pierre-francois.gimenez@inria.fr)
