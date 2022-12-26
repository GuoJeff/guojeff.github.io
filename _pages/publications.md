---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

See my most recent publications on <u><a href="https://scholar.google.com/citations?user=yzhfk_YAAAAJ&hl=en">Google Scholar</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
