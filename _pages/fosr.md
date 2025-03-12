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

## Download binary

You can download last compiled binaries from <https://github.com/Fos-R/Fos-R/releases/latest>.

## Compile from source

You can also compile Fos-R from source directly. Fos-R is distributed with [crates.io](https://crates.io/crates/fosr). First, install Rust with [rustup](https://rustup.rs/). Then, install the libpcap dependency. On Ubuntu/Debian, you can do:

`apt install libpcap-dev`

You can install Fos-R with:

`cargo install fosr`

Then, you can check the install with:

`fosr`

## Real-world uses

### BreizhCTF 2025

Fos-R created background network traffic during the [BreizhCTF 2025](https://www.breizhctf.com/) hacking competition for about 600 participants. During that competition, Fos-R was deployed on 750 virtual machines for a total of 23,000 cumulated hours.

### URSID

Fos-R is integrated as an option to [Ursid](https://ursid.readthedocs.io/en/latest/).

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
