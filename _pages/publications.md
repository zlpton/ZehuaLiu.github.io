---
layout: archive
title: "Published Papers"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Please click on the paper title to view the free download link and short summary.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
