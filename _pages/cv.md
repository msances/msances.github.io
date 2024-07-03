---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Academic Positions
======
* Temple University, Philadelphia, PA
	* Associate Professor, Department of Political Science, July 2022 -- present
	* Assistant Professor, Department of Political Science, July 2019 -- June 2022

* University of Memphis, Memphis, TN
	* Assistant Professor, Department of Political Science, August 2015 -- July 2019

* Vanderbilt University, Nashville, TN
	* Postdoctoral Fellow, Center for the Study of Democratic Institutions, August 2014 -- August 2015

Education
======
* Ph.D., Political Science, Massachusetts Institute of Technology, 2014
* B.A., Political Science, University of Massachusetts, 2006

Peer-Reviewed Publications
======
  {% for post in site.publications reversed %}
    {% unless post.status %}
      {% include archive-single-publication-cv.html %}
    {% endunless %}
  {% endfor %}

Working Papers
======
{% for post in site.publications reversed %}
  {% if post.status == "workingpaper" %}
    {% include archive-single-workingpaper.html %}
  {% endif %}
{% endfor %}

Other Publications
======
  {% for post in site.publications reversed %}
    {% if post.status %}
      {% unless post.status == "workingpaper" %}
        {% include archive-single-otherpublication-cv.html %}
      {% endunless %}
    {% endif %}
  {% endfor %}

Policy Reports, Opinion Pieces, and Blog Posts
======
  {% for post in site.writings reversed %}
    {% include archive-single-otherpublication-cv.html %}
  {% endfor %}
      
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
