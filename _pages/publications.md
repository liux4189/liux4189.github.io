---
layout: archive
title: "Publications [(Google Scholar Profile)](https://scholar.google.com/citations?hl=en&user=BCqHXQsAAAAJ)"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
