---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

* [_Entanglement Spectrum of Su-Schrieffer-Heeger-Hubbard Model_](http://connorlin.github.io)

__B. Ye__, L.-Z. Mu, H. Fan

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
