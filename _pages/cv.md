---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<a href="https://docs.google.com/viewer?url=https://github.com/tarafdar/cv/raw/master/naiftarafdar_cv.pdf" style="text-decoration: none;"><span class="fa-stack fa-1x" style="margin-right:1em"><i class="fa fa-file fa-2x"></i></span>Curriculum Vitae as PDF</a>

<h1 style="text-align: center; margin-top: 2em;">Naif Tarafdar</h1>

Education
======
* **Ph.D** at University of Toronto, 2020 (expected)
  * **Dissertation:** "Developing a Hardware Stack for Heterogeneous Data Centers"
  * **Advisor:** Paul Chow
* **M.A.Sc** at University of Toronto, 2016
  * **Thesis:** "Enabling Flexible Network FPGA Clusters in a Heterogeneous Data Center"
  * **Advisor:** Paul Chow
* **B.A.Sc with Honours in Computer Engineering** at University of Toronto


Industry And Research Experience
======
* **Xilinx Research:** Visiting Scholar - July 2018
  * I worked on integrating an optimized Xilinx Machine Learning Engine into my PhD research of a multi-FPGA and CPU framework. 

* **Xilinx Research:** Machine Learning Intern - August 2017 - December 2017
  * I designed, synthesized, and emulated, machine learning cores for high throughput, low-latency applications. I also worked on integrating these cores into popular software frameworks to make these cores accessible to software developers.  

* **IBM Canada:** Hardware Acceleration Lab Intern - May 2012 - September 2013
  * I optimized large-scale software projects CPU optimizations with the use of hardware accelerators and low-level software optimizations.  


Awards & Scholarships
======
* Queen Elizabeth II/Victoria Noakes Graduate Scholarship in Science and Technology - 2018
  * **Value:** $15000 
* Ontario Graduate Scholarship - 2016
  * **Value:** $15000 
* Edward S Rogers Sr. Graduate Scholarships - 2016
  * **Value:** $27400 
* Edward S Rogers Sr. Admission Scholarships - 2009
  * **Value:** $4000 


Publications
======
## Conferences ##
<ul>{% for post in site.publications %}
  {% if post.type == 'conf' %}
    {% include archive-single-cv.html %}
  {% endif %}
{% endfor %} </ul>

## Journals ##
<ul>{% for post in site.publications %}
  {% if post.type == 'journal' %}
    {% include archive-single-cv.html %}
  {% endif %}
{% endfor %} </ul>

## Book Chapters ##
<ul>{% for post in site.publications %}
  {% if post.type == 'book' %}
    {% include archive-single-cv.html %}
  {% endif %}
{% endfor %} </ul>

  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
<!--
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
-->
