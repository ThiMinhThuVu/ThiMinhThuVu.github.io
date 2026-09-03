---
title: Home
description: "Thi-Minh-Thu Vu — graduate researcher in surgical AI, biomedical image analysis, and multimodal medical AI."
permalink: /
---

## About

Hi! I’m **Thi-Minh-Thu Vu** (**Vũ Thị Minh Thư**), a graduate researcher in AI for healthcare. My research focuses on **Surgical AI, Biomedical Image Analysis, and Multimodal Medical AI**.

My earlier work explored question answering, evidence retrieval, scientific document understanding, and biomedical multi-hop reasoning. I am now extending these interests to surgical video understanding: enabling AI systems to interpret surgical scenes, reason over temporal and anatomical context, retrieve supporting visual evidence, and make clinically reliable predictions.

I am particularly interested in systems that answer not only *“What does the model predict?”* but also *“What visual evidence supports this prediction, why did the surgical event occur, and can the prediction be trusted clinically?”*

<p class="research-path" aria-label="Research trajectory"><span>Evidence Retrieval</span><b>→</b><span>Question Answering</span><b>→</b><span>Biomedical QA</span><b>→</b><span>Multimodal Reasoning</span><b>→</b><span>Surgical Video Understanding</span><b>→</b><span>Trustworthy Surgical AI</span></p>

## Research Interests

<ul class="interest-grid">
  <li>Surgical AI</li><li>Biomedical Image Analysis</li><li>Surgical Video Understanding</li>
  <li>Surgical Scene Understanding</li><li>Surgical Video Question Answering</li><li>Vision-Language &amp; Multimodal Learning</li>
  <li>Temporal Grounding &amp; Video Retrieval</li><li>Scene Graphs &amp; Structured Surgical Knowledge</li>
  <li>Trustworthy / Safety-Aware AI for Surgery</li><li>Evidence Retrieval &amp; Biomedical QA</li>
</ul>

## Selected Research

### Evidence-grounded Surgical VideoQA

Developing multimodal systems that jointly answer surgical questions and retrieve the temporal visual evidence supporting each answer. [Read more about my research →]({{ '/research/' | relative_url }})

### Structured and Trustworthy Surgical AI

Studying temporal scene graphs, anatomical relationships, and uncertainty-aware analysis to build safer, more interpretable surgical AI systems. [View current projects →]({{ '/projects/' | relative_url }})

## Selected Publications

{% include publication-list.html show_years=false %}

[View all publications →]({{ '/publications/' | relative_url }})

## Teaching

{% for item in site.data.teaching %}
<div class="teaching-entry">
  <h3>{{ item.role }} · {{ item.term }}</h3>
  <p><strong>{{ item.course_code }}: {{ item.course_title }}</strong><br>
  {{ item.unit }} · Instructor: {{ item.instructor }}</p>
</div>
{% endfor %}

## News

<ul class="news-list">
{% for item in site.data.news %}
  <li><strong>[{{ item.date }}]</strong> {{ item.text }}</li>
{% endfor %}
</ul>
