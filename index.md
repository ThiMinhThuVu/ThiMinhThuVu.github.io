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

<h2 id="news">🔥 News</h2>

<ul class="news-list">
{% for item in site.data.news %}
  <li><span aria-hidden="true">{{ item.icon }}</span> <span>{{ item.date }}:</span> {{ item.text }}</li>
{% endfor %}
</ul>

## Publications

{% include publication-list.html %}

## Education

[2022.09 - 2026.06] **B.Sc. in Computer Science**, [Vietnam National University, University of Engineering and Technology (VNU-UET)](https://uet.vnu.edu.vn/en/).<br>
GPA: **3.8/4.0**, top 8% of cohort.

## Experience

### Research Experience

- [2026.06 - Present] **Research Assistant — VinUni-Illinois Smart Health Center, VinUniversity**<br>
  ◦ Advised by Dr. [Huy-Hieu Pham](https://huyhieupham.github.io/).<br>
  ◦ Anatomical segmentation, surgical scene understanding, and scene graphs for knowledge-enhanced visual question answering.
- [2026.06 - Present] **Research Associate — [PASSIO Lab](https://www.passiolab.com/), North Carolina A&T State University, USA**<br>
  ◦ Advised by Dr. [Phat K. Huynh](https://scholar.google.com/citations?user=Wo5c6BEAAAAJ&hl=vi).<br>
  ◦ Deep learning and temporal modeling for phase recognition in cardiac surgery videos.
- [2023.09 - 2026.06] **Research Assistant — Data Science and Knowledge Technology Laboratory**<br>
  ◦ Advised by Dr. [Hoang-Quynh Le](https://scholar.google.com/citations?user=LBYOZ00AAAAJ&hl=vi).<br>
  ◦ Heterogeneous graphs for citation-aware summarization and retrieval-augmented pipelines for multi-hop biomedical question answering.

### Teaching Experience

[2026.07 - Present] **Teaching Assistant — College of Engineering & Computer Science, VinUniversity.**

<ul>
{% for item in site.data.teaching %}
  <li class="teaching-entry">
    <p><strong>[{{ item.term }}]</strong> {{ item.course_code }} - {{ item.course_title }} @ {{ item.unit }}<br>◦ Instructor: <a href="{{ item.instructor_url }}">{{ item.instructor }}</a></p>
  </li>
{% endfor %}
</ul>

### Industry Experience

[2025.10 - 2025.12] **AI Engineer Intern — R&D Department, MBBank**<br>
Developed information retrieval for enterprise question-answering and Text-to-SQL chatbots, including schema graph retrieval, prompt engineering, and entity extraction.

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
