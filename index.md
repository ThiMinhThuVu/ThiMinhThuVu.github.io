---
title: Home
description: "Thu T.M Vu — graduate researcher in surgical AI, biomedical image analysis, and multimodal medical AI."
permalink: /
---

## About

Hi! I’m Thi-Minh-Thu Vu, a research assistant at [VinUni-Illinois Smart Health Center (VISHC)](https://smarthealth.vinuni.edu.vn/).

My earlier work explored question answering, evidence retrieval, scientific document understanding, and biomedical multi-hop reasoning. I am now extending these interests to surgical video understanding: enabling AI systems to interpret surgical scenes, reason over temporal and anatomical context, retrieve supporting visual evidence, and make clinically reliable predictions.

I am particularly interested in systems that answer not only “What does the model predict?” but also “What visual evidence supports this prediction, why did the surgical event occur, and can the prediction be trusted clinically?”

## Research Interests

<ul class="interest-grid">
  <li>Biomedical Image Analysis</li>
  <li>Scene Graphs &amp; Structured Surgical Knowledge</li>
  <li>Video Question Answering</li>
  <li>Trustworthy AI</li>
</ul>

## Education

**B.Sc. in Computer Science**, Vietnam National University, University of Engineering and Technology (VNU-UET), Sep. 2022–Jun. 2026. GPA: **3.8/4.0**, top 8% of cohort.

## Research Experience

- **Research Assistant — VinUni-Illinois Smart Health Center, VinUniversity** (Jun. 2026–present). Advised by Dr. Huy-Hieu Pham. Anatomical segmentation, surgical scene understanding, and scene graphs for knowledge-enhanced visual question answering.
- **Research Associate — PASSIO Lab, North Carolina A&T State University** (Jun. 2026–present). Advised by Dr. Phat K. Huynh. Deep learning and temporal modeling for phase recognition in cardiac surgery videos.
- **Research Assistant — Data Science and Knowledge Technology Laboratory** (Sep. 2023–Jun. 2026). Advised by Dr. Hoang-Quynh Le. Heterogeneous graphs for citation-aware summarization and retrieval-augmented pipelines for multi-hop biomedical question answering.

## Industry Experience

**AI Engineer Intern — R&D Department, MBBank** (Oct.–Dec. 2025). Developed information retrieval for enterprise question-answering and Text-to-SQL chatbots, including schema graph retrieval, prompt engineering, and entity extraction.

## Publications

{% include publication-list.html %}

## Teaching Assistant

{% for item in site.data.teaching %}
<div class="teaching-entry">
  <p><strong>[{{ item.term }}]</strong> {{ item.course_code }} - {{ item.course_title }} @ {{ item.unit }} - Instructor: <a href="{{ item.instructor_url }}">{{ item.instructor }}</a></p>
</div>
{% endfor %}

## Honors and Awards

- [2026] **Outstanding Undergraduate Thesis, VNU-UET.** Ranked 1st in the thesis evaluation committee with a score of 9.7/10.
- [2026] **Third Prize, TIGER SQ-AI Challenge at MICCAI.** Ranked 3rd in the Biomedical Image Segmentation task.
- [2026] **6th Place, FOMO26: The Foundation Model Challenge for Brain MRI at MICCAI.** Ranked 6th among 33 participating teams.
- [2026] **Second Prize, NUS Young Fellowship Poster Competition.** Ranked 2nd in the research poster competition at the National University of Singapore.
- [2026] **Second Prizes, Undergraduate Scientific Research Conference at UET.**
- [2025] **Second Prize, BioCreative IX at IJCAI, Track 1: MedHopQA.** International competition on Large Language Models for Clinical and Biomedical NLP.
- [2025] **Third Prize, Undergraduate Scientific Research Conference at FIT-UET.**
- [2025] **Student of 5 Good Merits Award, UET.**

## Fellowships & Scholarships

- [2026] **NUS Young Fellowship Programme.** Selected for a funded one-month fellowship programme in AI at the National University of Singapore.
- [2023–2026] **Vingroup Talent Scholarship.** Awarded to three outstanding students at UET for excellence in academic performance and research achievements.
- [2023–2026] **UET Annual Scholarship for Outstanding Students.** Awarded to the top 8% of students with the highest GPA.
- [2023] **Dong Hanh Scholarship.** Awarded to students demonstrating strong academic performance, determination, and perseverance.

## News

<ul class="news-list">
{% for item in site.data.news %}
  <li><strong>[{{ item.date }}]</strong> {{ item.text }}</li>
{% endfor %}
</ul>
