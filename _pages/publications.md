---
permalink: /publications/
title: "Publications"
author_profile: true
---

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
