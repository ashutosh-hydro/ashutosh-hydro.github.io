---
layout: archive
title: "Publications"
permalink: /articles/
author_profile: true
---
You can also find my articles on <u><a href="https://scholar.google.co.in/citations?user=15sE22kAAAAJ&hl=en">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}