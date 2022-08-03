---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download PDF](/files/aronson-cv.pdf)

Education
------
* Ph. D. in Robotics, Carnegie Mellon University, 2022
  * Advisor: [Henny Admoni](http://hennyadmoni.com/)
* M. S. in Robotics, Carnegie Mellon University, 2018
  * Advisor: [Henny Admoni](http://hennyadmoni.com/)
* B. S. in Mechanical Engineering, Massachusetts Institute of Technology, 2012

Publications
======
## Thesis work

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

{% comment %} 
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
{% endcomment %}



Work experience
======
**Mechanical Engineer, Naval Research Laboratory (Contractor with Exelis, Inc.)**<br />
*Washington, DC — July 2012 to June 2015*

<!--
NRL code 5775 (Special Projects Group) works on various projects related to electronic warfare and radar.
* Work closely with the mechanical and electrical design teams to provide support and ensure software compatibility, and participate in mechanical and electrical design reviews
* Conduct major tests and exercises, including leading a team of three aboard the USS Spruance in July 2014 for a five-country, four-day test event as part of the Navy’s biennial RIMPAC exercises -->

{% comment %}
### Experimental Studies Group (Teaching Assistant)
*MIT — Fall 2009-Spring 2012*

<!-- 
In ESG, a freshman learning community, first-year students complete institute requirements in small classes supported by accessible teachers and upperclassmen.
* Assisted with Calculus 1 and 2 (accelerated), Differential Equations, Physics II (advanced), and Linear Algebra
* Taught well-attended regular recitation sections and held office hours to augment lectures
* Graded problem sets and exams
-->


### General Electric Flow Gas and Moisture (Mechanical Engineering Intern)
*Billerica, MA — Summer 2011*

<!--
Research and development team of GE FG&M investigating novel ways of measuring fluid flow rates through pipes.
* Designed, analyzed, and tested ultrasonic offset flowmeter prototype
* Performed additional tests of other early-stage prototypes and assisted in their design
* Presented on summer work to other engineers and interns 
* Patent resulting from summer work
-->

{% endcomment %}

Skills
======
* Programming languages: C++, Python, LaTeX, MATLAB
* Software: ROS, MATLAB, Solidworks, Linux
* Fabrication equipment: Mill (manual and CNC), lathe, laserjet, waterjet, 3D printer

Service
======
* Reviewer for AURO 2018, HRI 2018-2022, HUMANOIDS 2016-2017, 2019, IEEE VR 2019, IROS 2018, RA-L 2021, RO-MAN 2021, RSS 2019, THRI 2020-2021, UIST 2019
* Co-founder and organizer of the CMU [HRI Reading Group](http://harp.ri.cmu.edu/reading-group/), 2018-present
* Founding member of [CMU Tech4Society](http://www.tech4society.group/), 2016-2019
* Founding member of the SCS4All PhD Initiative, which advocates for and supports PhD students at the CMU School of Computer Science, 2017-2019
