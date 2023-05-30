---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

* [_Measuring out-of-time-order correlators on a nuclear magnetic resonance quantum simulator_](https://physics.aps.org/articles/v10/82)  
J. Li, R.-H. Fan, H.-Y. Wang, __B. Ye__, B. Zeng, H. Zhai, X.-H. Peng, J.-F. Du
__Phy. Rev. X__ 7, 031011 (2017)  
     Physics Viewpoint: [_Seeing Scrambled Spins_](https://physics.aps.org/articles/v10/82)

* [_Entanglement Spectrum of Su-Schrieffer-Heeger-Hubbard Model_](http://journals.aps.org/prb/abstract/10.1103/PhysRevB.94.165167))  
__B. Ye__, L.-Z. Mu, H. Fan  
__Phy. Rev. B__ 94, 165167 (2016)

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
