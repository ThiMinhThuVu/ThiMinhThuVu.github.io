---
title: Home
description: "Thu T.M Vu — graduate researcher in surgical AI, biomedical image analysis, and multimodal medical AI."
permalink: /
---

## About

Hi! I’m Thu T.M Vu, a graduate researcher in AI for healthcare. My research focuses on Surgical AI, Biomedical Image Analysis, and Multimodal Medical AI.

My earlier work explored question answering, evidence retrieval, scientific document understanding, and biomedical multi-hop reasoning. I am now extending these interests to surgical video understanding: enabling AI systems to interpret surgical scenes, reason over temporal and anatomical context, retrieve supporting visual evidence, and make clinically reliable predictions.

I am particularly interested in systems that answer not only “What does the model predict?” but also “What visual evidence supports this prediction, why did the surgical event occur, and can the prediction be trusted clinically?”

<p class="research-path" aria-label="Research trajectory"><span>Evidence Retrieval</span><b>→</b><span>Question Answering</span><b>→</b><span>Biomedical QA</span><b>→</b><span>Multimodal Reasoning</span><b>→</b><span>Surgical Video Understanding</span><b>→</b><span>Trustworthy Surgical AI</span></p>

## Research Interests

<ul class="interest-grid">
  <li>Surgical Video Understanding</li>
  <li>Surgical Video Question Answering</li>
  <li>Scene Graphs &amp; Structured Surgical Knowledge</li>
</ul>

## Publications

{% include publication-list.html show_years=false %}

## Teaching Assistant

{% for item in site.data.teaching %}
<div class="teaching-entry">
  <p>[{{ item.term }}] {{ item.course_code }} - {{ item.course_title }} @ {{ item.unit }} - Instructor: {{ item.instructor }}</p>
</div>
{% endfor %}

## News

<ul class="news-list">
{% for item in site.data.news %}
  <li>[{{ item.date }}] {{ item.text }}</li>
{% endfor %}
</ul>
