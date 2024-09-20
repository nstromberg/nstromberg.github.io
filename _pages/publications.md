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

Selected Work
===

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

All Publications
===
<script src="https://bibbase.org/show?bib=https://dblp.org/pid/293/2005-1.bib&noBootstrap=1&jsonp=1"></script> 