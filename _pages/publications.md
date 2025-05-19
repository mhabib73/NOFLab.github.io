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

**No Double Descent in Principal Component Regression: A High-Dimensional Analysis**,
**DG**, Antônio H. Ribeiro, Thomas B. Schön,
*ICML*, 2024.\
[OpenReview](https://openreview.net/forum?id=M4ejBhNNrn){: .btn--research}{:target="_blank"}
[ICML](https://icml.cc/virtual/2024/poster/34254){: .btn--research}{:target="_blank"}
[code](https://github.com/dgedon/PCR_spiked_covariance){: .btn--research}{:target="_blank"}
[download](/files/pdf/research/Mahfuz_Ultra_IEEE_Access_2024.pdf){: .btn--research}{:target="_blank"}
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<sup>*</sup> Equal authorship
