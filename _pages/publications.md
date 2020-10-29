---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

;{% if author.googlescholar %}
;  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
;{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<br>
<b>[Autoregressive Score Matching](http://lantaoyu.com/publications/ARSM)</b> <br> 
Chenlin Meng, <b>Lantao Yu</b>, Yang Song, Jiaming Song, and Stefano Ermon.
<i>The 34th Conference on Neural Information Processing Systems</i>. <b>NeurIPS 2020</b>.
