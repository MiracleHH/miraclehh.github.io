---
layout: archive
title: "Publications"
#permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## 2021
<p>
<b><font color=blue>Data Poisoning Attacks to Deep Learning Based Recommender Systems</font></b><br/>
<b>Hai Huang</b>, Jiaming Mu, Neil Zhenqiang Gong, Qi Li, Bin Liu, Mingwei Xu.<br/>
In ISOC Network and Distributed System Security Symposium (NDSS), 2021<br/>
[[pdf](https://www.ndss-symposium.org/wp-content/uploads/ndss2021_6C-4_24525_paper.pdf)]
</p>

