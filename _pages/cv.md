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
* B.S. in University of Science and Technology of China (USTC) from 2018 to 2022, majored in Physics
* Ph.D candidate in University of Hong Kong, from 2022 to now, majored in Electronic Engineering

Reseach Experience
======
* Non-linear Function Generation by RRAM-based ADC
  * 2022.11-2023.07
  * In a MANN based Few-shot learning task implemnted on circuits, ADCs are required to help calculate Hamming Distance between Query set and Support set. The accuracy of NN inference, however, will exponetially decrease when ADC precision is limited. Thus, we need a RRAM-based ADC to non-linearly transfer the Hamming distance distribution to a uniform ditribution. This work obviously improve inference accuracy when ADC precision is limited.
  * Supervisor: Assistant Prof. Can Li

* Efficient Transformer implemented on circuit.
  * 2023.07-Now
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

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
  
Service and leadership
======
* Currently signed in to 43 different slack teams
