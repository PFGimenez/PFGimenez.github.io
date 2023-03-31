---
title: "Un système agnostique de détection d’intrusion radio pour protéger l’Internet des objets"
collection: talks
type: "Talk"
venue: "Nouvelles Avancées en Sécurité des Systèmes d'Information, INSA-Toulouse"
date: 2020-01-22
location: "Toulouse, France"
---

L'expansion de l'Internet des objets (IoT) entraîne l'apparition de maisons intelligentes, d'usines intelligentes et même de villes intelligentes. Bien que ces objets améliorent la qualité de vie de ses utilisateurs et offrent de nouvelles opportunités économiques, ils sont aussi un important vecteur d'attaques (le botnet Mirai étant sûrement l'exemple le plus connu). Pour protéger ces environnements, des systèmes de détection d'intrusion (IDS) sont développés. Ces IDS rencontrent des problématiques uniques à l'IoT, telles que l'évolution rapide des technologies et des protocoles ou encore leur réseau décentralisé. Pour surmonter ces problèmes, nous proposons un IDS qui surveille de larges bandes de fréquences au niveau de la couche physique sans faire d'hypothèses sur les protocoles ou les technologies présentes. De plus, notre solution propose pour chaque attaque détectée un diagnostic triple : temporel (les dates exactes de l'anomalie détectée), fréquentiel (la fréquence principale de l'anomalie) et spatial (la position estimée de l'origine de l'anomalie). Nous avons expérimenté notre méthode avec une expérimentation grandeur nature: notre système a pu efficacement détecter et diagnostiquer les attaques lancées sur les bandes 400-500 MHz et 800-900 MHz, deux bandes qui ne sont pas couvertes par les solutions traditionnelles. [Slides](https://pfgimenez.github.io/files/nassi.pdf)
