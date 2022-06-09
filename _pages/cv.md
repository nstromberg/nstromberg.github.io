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
* B.S. in Computer Science, University of Kentucky, 2021
* Ph.D in Electrical Engineering, Arizona State University, 2026 (expected)

Research Appointments
======
* Summer 2021 - Present:
  * Worked with Dr. Lalitha Sankar and collaborators to evaluate a novel risk prediction method for noisy data
* Fall 2020 - Summer 2021:
  * Worked with Dr. Lalitha Sankar and collaborators to train and evaluate logistic regression models on novel COVID-19 dataset
* Summer 2020: Undergraduate Researcher, SURI Program, Arizona State University
  * Worked with Dr. Lalitha Sankar and collaborators to evaluate a tunable class of loss functions, $\alpha$-loss
  * Ran large scale PyTorch code on large computing cluster

Work experience
======
* Summer 2019: Software Engineering Intern, GE Applicances, a Haier Company
  * Worked with AWS Lambda and AWS Connect to build user-facing APIs
  * Eliminated On-Phone wait time for up to 8,000 customers per day through custom callback feature

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
