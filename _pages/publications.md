---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on my <a href="https://scholar.google.com/citations?user=2DDHCTkAAAAJ">Google Scholar profile</a> and on <a href="https://haltools.archives-ouvertes.fr/Public/afficheRequetePubli.php?auteur_exp=Pierre-Fran%C3%A7ois,%20Gimenez&CB_auteur=oui&CB_titre=oui&CB_article=oui&langue=Anglais&tri_exp=annee_publi&tri_exp2=typdoc&tri_exp3=date_publi&ordre_aff=TA&Fen=Aff&css=../css/VisuRubriqueEncadre.css">HAL</a>.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
