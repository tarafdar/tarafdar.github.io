---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}


Conferences
======
{% for post in site.publications.conf reversed %}
  {% include archive-single.html %}
{% endfor %}

Journals
======
{% for post in site.publications.journal reversed %}
  {% include archive-single.html %}
{% endfor %}

Book Chapters
======
{% for post in site.publications.books reversed %}
  {% include archive-single.html %}
{% endfor %}
