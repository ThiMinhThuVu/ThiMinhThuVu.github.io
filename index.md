---
title: Home
description: "Thu T.M Vu — graduate researcher in surgical AI, biomedical image analysis, and multimodal medical AI."
permalink: /
---

## About

Hi! I’m Thu T.M Vu, a graduate student at VNU University of Engineering and Technology (VNU-UET). My research focuses on Surgical AI, Biomedical Image Analysis, and Multimodal Medical AI.

My earlier work explored question answering, evidence retrieval, scientific document understanding, and biomedical multi-hop reasoning. I am now extending these interests to surgical video understanding, with an emphasis on interpreting surgical scenes, reasoning over temporal and anatomical context, and retrieving supporting visual evidence.

I am particularly interested in evidence-grounded and trustworthy systems that connect predictions with the visual evidence supporting them.

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
