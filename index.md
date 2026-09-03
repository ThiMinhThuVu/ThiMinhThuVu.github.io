---
title: Home
description: "Thu T.M Vu — graduate researcher in surgical AI, biomedical image analysis, and multimodal medical AI."
permalink: /
---

## About

Hi! I’m Thi-Minh-Thu Vu, a research assistant at [VinUni-Illinois Smart Health Center (VISHC)](https://smarthealth.vinuni.edu.vn/). My research focuses on Surgical AI, Biomedical Image Analysis, and Multimodal Medical AI.

My earlier work explored question answering, evidence retrieval, scientific document understanding, and biomedical multi-hop reasoning. I am now extending these interests to surgical video understanding: enabling AI systems to interpret surgical scenes, reason over temporal and anatomical context, retrieve supporting visual evidence, and make clinically reliable predictions.

I am particularly interested in systems that answer not only “What does the model predict?” but also “What visual evidence supports this prediction, why did the surgical event occur, and can the prediction be trusted clinically?”

## Research Interests

<ul class="interest-grid">
  <li>Surgical Video Understanding</li>
  <li>Surgical Video Question Answering</li>
  <li>Scene Graphs &amp; Structured Surgical Knowledge</li>
  <li>Trustworthy Surgical AI</li>
</ul>

## Publications

{% include publication-list.html %}

## Teaching Assistant

{% for item in site.data.teaching %}
<div class="teaching-entry">
  <p><strong>[{{ item.term }}]</strong> {{ item.course_code }} - {{ item.course_title }} @ {{ item.unit }} - Instructor: <a href="{{ item.instructor_url }}">{{ item.instructor }}</a></p>
</div>
{% endfor %}

## News

<ul class="news-list">
{% for item in site.data.news %}
  <li><strong>[{{ item.date }}]</strong> {{ item.text }}</li>
{% endfor %}
</ul>
