---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}


* [TMC] Mozi Chen, SWIM: Speed-aware WiFi-based Passive Indoor Localization for Mobile Ship Environment, IEEE Transactions on Mobile Computing, 2019.[PDF](http://treegod13.github.io/files/paper0.pdf)


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
