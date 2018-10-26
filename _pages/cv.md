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
------
* B. S. in Mechanical Engineering, Massachusetts Institute of Technology, 2012
  * Minor: Ancient-Medieval Studies
* M. S. in Robotics, Carnegie Mellon University, 2018
* Ph. D. in Robotics, Carnegie Mellon University, 2021 (expected)

Work experience
------
### Mechanical Engineer, Naval Research Laboratory (Contractor with Exelis, Inc.)
*Washington, DC — July 2012 to present*

NRL code 5775 (Special Projects Group) works on various projects related to electronic warfare and radar.
* Work closely with the mechanical and electrical design teams to provide support and ensure software compatibility, and participate in mechanical and electrical design reviews
* Conduct major tests and exercises, including leading a team of three aboard the USS Spruance in July 2014 for a five-country, four-day test event as part of the Navy’s biennial RIMPAC exercises

### Experimental Studies Group (Teaching Assistant)
*MIT — Fall 2009-Spring 2012*

In ESG, a freshman learning community, first-year students complete institute requirements in small classes supported by accessible teachers and upperclassmen.
* Assisted with Calculus 1 and 2 (accelerated), Differential Equations, Physics II (advanced), and Linear Algebra
* Taught well-attended regular recitation sections and held office hours to augment lectures
* Graded problem sets and exams

### General Electric Flow Gas and Moisture (Mechanical Engineering Intern)
*Billerica, MA — Summer 2011*

Research and development team of GE FG&M investigating novel ways of measuring fluid flow rates through pipes.
* Designed, analyzed, and tested ultrasonic offset flowmeter prototype
* Performed additional tests of other early-stage prototypes and assisted in their design
* Presented on summer work to other engineers and interns 
* Patent resulting from summer work

  
Skills
======
* Programming languages: C++, Python, LaTeX, MATLAB
* Software: ROS, MATLAB, Solidworks, Linux
* Fabrication and experimentation equipment: Mill (manual and CNC), lathe, waterjet and laserjet, 3D printer

Publications
======
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
  
<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul> -->
  
<!-- Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
  
Service and leadership
======
* Founding member of [CMU Tech4Society](http://www.tech4society.group/)
* Member of the SCS4All PhD Initiative, a group of Ph. D. students at SCS working to improve the graduate student experience
