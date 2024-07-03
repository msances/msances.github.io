---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
{% include base_path %}

<h3>Working Papers</h3>
{% for post in site.publications reversed %}
  {% if post.status == "workingpaper" %}
    {% include archive-single-workingpaper.html %}
  {% endif %}
{% endfor %}

<h3>Publications</h3>
<h3>Forthcoming</h3>
{% for post in site.publications reversed %}
  {% if post.forthcoming %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
{% assign postsByYear =
    site.publications | group_by_exp:"post", "post.date | date: '%Y'" %}
{% for year in postsByYear reversed %}
  <h3>{{ year.name }}</h3>
      {% for post in year.items reversed %}
        {% if post.status != "workingpaper" %}
          {% unless post.forthcoming %}
            {% include archive-single.html %}
          {% endunless %}
        {% endif %}
      {% endfor %}
{% endfor %}

