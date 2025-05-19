---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

**Deep networks for system identification: a Survey**,
Gianluigi Pillonetto, Aleksandr Aravkin, **DG**, Lennart Ljung, Antônio H. Ribeiro, Thomas B. Schön,
Automatica, 2025.\
[doi](https://doi.org/10.1016/j.automatica.2024.111907){: .btn--research}{:target="_blank"}
[arXiv](https://arxiv.org/abs/2301.12832){: .btn--research}{:target="_blank"}

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<sup>*</sup> Equal authorship
