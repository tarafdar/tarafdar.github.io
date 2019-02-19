---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <u><a href="https://scholar.google.ca/citations?user=MB0KVeoAAAAJ&hl=en&oi=ao">my Google Scholar profile</a>.</u>

{% include base_path %}


## Conferences ##
======
{% for post in site.publications reversed %}
  {% if post.type == 'conf' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Journals ##
======
{% for post in site.publications reversed %}
  {% if post.type == 'journal' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Book Chapters ##
======
{% for post in site.publications reversed %}
  {% if post.type == 'book' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
