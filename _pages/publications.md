---
permalink: /publications/
title: "Research"
author_profile: true
---

## Working Papers

{% for post in site.publications reversed %}
  {% if post.publication_type == "working paper" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Publications

{% for post in site.publications reversed %}
  {% if post.publication_type != "working paper" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
