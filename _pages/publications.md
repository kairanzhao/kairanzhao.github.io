---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

**PhD**

* [NeurIPS 2023 - Machine Unlearning](https://kaggle.com/competitions/neurips-2023-machine-unlearning), Eleni Triantafillou, Fabian Pedregosa, Jamie Hayes, Peter Kairouz, Isabelle Guyon, Meghdad Kurmanji, Gintare Karolina Dziugaite, Peter Triantafillou, **Kairan Zhao**, Lisheng Sun Hosoya, Julio C. S. Jacques Junior, Vincent Dumoulin, Ioannis Mitliagkas, Sergio Escalera, Jun Wan, Sohier Dane, Maggie Demkin, Walter Reade.

**Pre-PhD**

* [A Secure Intra-Regional-Inter-Regional Peer-to-Peer Electricity Trading System for Electric Vehicles](https://ieeexplore.ieee.org/abstract/document/9891809), **Kairan Zhao**, Meng Zhang, Rongxing Lu, Chao Shen. IEEE Transactions on Vehicular Technology, 2022.
