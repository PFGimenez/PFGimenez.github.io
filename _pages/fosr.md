---
layout: archive
permalink: /fosr/
title: "Fos-R"
author_profile: true
redirect_from: 
  - /fosr.html
  - /fos-r/
  - /fos-r.html
---

{% include base_path %}

Fos-R aims to generate realistic and diverse network and system activity from patterns learned from actual data.

## Related software

{% for post in site.software reversed %}
  {% if post.fosr %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Related publications

{% for post in site.publications reversed %}
  {% if post.fosr %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Scientific contributors

- Inria: Pierre-François Gimenez, Yufei Han, Ludovic Mé, Adrien Schoen
- CISPA: Lénaïg Cornanguer, Joscha Cüppers
- Télécom SudParis: Grégory Blanc
- DGA: Frédéric Majorczyk

## Software contributors

- Inria: Pierre-François Gimenez, Adrien Schoen
- CISPA: Lénaïg Cornanguer, Joscha Cüppers
- CentraleSupélec: Evan Morin, Florentin Labelle

## Links

<https://github.com/Fos-R>
