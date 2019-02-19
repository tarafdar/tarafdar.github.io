---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>

{% include base_path %}


Conferences
======
{% for post in site.publications.conf reversed %}
  {% if post.type == 'journal' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

Journals
======
{% for post in site.publications reversed %}
  {% if post.type == 'journal' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

Book Chapters
======
{% for post in site.publications reversed %}
  {% if post.type == 'book' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
