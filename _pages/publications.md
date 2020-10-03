---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my publications on my <u><a href="https://scholar.google.com/citations?hl=en&user=xaY1UPgAAAAJ">Google Scholar</a></u> profile.
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

