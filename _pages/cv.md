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

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-publication-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
