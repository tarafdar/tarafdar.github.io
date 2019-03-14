---
layout: single
title: "Publications Organised by Type"
permalink: /publications-by-type/
author_profile: true
---
{% include base_path %}

{% if site.author.googlescholar or site.author.dblp %} 
You can also find my publications on {% if site.author.dblp %} <a href="{{site.author.dblp}}">my dblp profile</a> {% endif %} {% if site.author.googlescholar and site.author.dblp %} and {% endif %} {% if site.author.googlescholar %} <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>{% endif %}.
{% endif %}

You can also find my publications also [organised by publication date](/publications/).

{% include publication_types %}
<h3>Publication Type</h3>
<ul style="padding-left: 2em;">
{% for type in types  %}
  {% if type == '' %}
    {% continue %}
  {% endif %}
<li style="margin-bottom: 0em;"><strong><a href="#{{type | downcase | replace:' ','-'}}">{{type}}{% if type != 'Thesis' %}s{% endif %}</a></strong></li>
{% endfor %}
</ul>

{% include publications_list_by_type %}
