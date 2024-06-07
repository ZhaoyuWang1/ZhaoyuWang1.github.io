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
* MSc in Artificial Intelligence, Imperial College London, 2022-2023
* BEng in Electronic & Electrical Engineering, UCL, 2019-2022

Work experience
======
* Spring 2024 - present: AI Engineer
  * Huawei Tech Co., Ltd.
  * Duties includes: application of LLMs under smart industrial campus scenario. 

* Summer 2021: Privacy and Security Intern
  * Midea Co., Ltd
  * Duties includes:
    * Investigate and survey the existing standards and techniques for security of IoT.
    * Help execute vulnerability scanning for hardware and software of IoT modules from the
      company's products.
    * Attend in deploying the working environment with Docker.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Projects & Activities
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Skills
======
* Programming Language: Python, Java, C, Hardware Description Language: SystemVerilog
* Electronic Simulation: Multism, ModelSim, Simulink, Quartus
* Mathematical Modelling & Analysis: Matlab, Python
* Languages: Mandarian (First Language), English (Professional)
