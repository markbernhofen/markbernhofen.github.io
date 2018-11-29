---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* MEng (First Class Honours) in Civil & Structural Engineering, University of Leeds, 2017
* Study Abroad Year, Dept. of Civil & Environmental Engineering, University of Illinois at Urbana-Champaing, 2016 
  
Skills
======
* GIS
* Python
* MATLAB
* Microsoft Office

Languages
======
* English (Fluent)
* German (Fluent)

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
