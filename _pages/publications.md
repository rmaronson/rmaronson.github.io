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

## Thesis

  {% for post in site.publications reversed %}
    {% if post.pubtype == "thesis" %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}

## Journal papers

  {% for post in site.publications reversed %}
    {% if post.pubtype == "journal" %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}

## Conference papers

  {% for post in site.publications reversed %}
    {% if post.pubtype == "conference" %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}

## Workshop papers

  {% for post in site.publications reversed %}
    {% if post.pubtype == "workshop" %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}
