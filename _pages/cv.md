---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

My CV is <u><a href="{{author.googlescholar}}">here</a>.</u>

Education
======
* M.S. in Statistics, University of Chicago, 2023 (expected)
* B.A. in Political Science (Minor in Law, Certificate in Data Science), Waseda University, 2021

  
Skills
======
* R, Python, Latex, 
* Language: Japanese (native), English (fluent)

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
