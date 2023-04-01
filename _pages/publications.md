---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- {% if author.googlescholar %} -->
<!-- You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u> -->
<!-- {% endif %} -->
You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?user=2e1sfqAAAAAJ&hl=en&authuser=1)

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
