---
permalink: /
title: "Biography"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- [中文简历](../files/cv_zh.pdf) [English CV](../files/cv_en.pdf) -->

Currently I am an undergraduate student of the AI school in Beihang University.

<!-- My research focuses on the exploration and development of generative and pre-trained models, aiming to deeply understand their wide applications in the scientific domain. This includes utilizing generative models for targeted drug design, innovative protein structure design, and the construction of pre-trained models for biological structures. -->

Education
======
* B.S., Beihang University, 2021 - now

Internships
======
* Baidu Paddle (PLCC), 2024.7 - 2024.9
* Shanghai AI Lab (Research Intern), 2024.9 - now

Publications/Preprints
======
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

<ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Academic Services
======
* Conference Reviewer: NeurIPS, ICLR

More
======
TBD

<!-- Honors & Awards
======  -->

<!-- Academic Services
====== -->


