---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on [Thuan Nguyen Duc](https://scholar.google.com/citations?user=oyq0uo0AAAAJ&hl=en)
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
