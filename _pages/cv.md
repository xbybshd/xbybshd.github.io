---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Research Interest
======
* **Computational Structural Biology**: Molecular dynamics, Protein structure prediction, CADD
* **Computer Science**: Deep Learning, High performance computing
  
Course Learned
======
[Course Learned](https://xbybshd.github.io/course/)

Education
======
* **Fudan University**, Shanghai, China, 2012.9-2017.6
  * B.S. in Life Sciences, GPA 3.03/4
  * Advisor: Prof. Yao Li
* **Fudan University**, Shanghai, China, 2017.9-2021.1
  * M.S. in Software Engineering, GPA 3.34/4
  * Supervisor: Prof. Yanchun Zhang


Work experience
======
* **Kuaishou Technology**, Beijing, China, 2021.3-present
  * Search Technology Department
  * C++ R&D Engineer
  * Search engine developing and performance optimization, Linux C++ multi-threaded program development, cpu performance analysis optimization
  * Search engine relevance model optimization (Bert model), inference acceleration on Bert, AI compilation optimization based on TVM
  * Search engine posterior model engineering (Recommend system model, SIM)
    * Participating the algorithm project "Query-dominant User Interest Network for Large-Scale Search Ranking. [CIKM 2023](https://dl.acm.org/doi/10.1145/3583780.3615022)

Research Experience
======
* **Prescription Recommendation System for Traditional Chinese Medicine Prescriptions by Machine Learning and Deep Learning**
  * PI: Yanchun Zhang
  * Software School of Fudan University
  * Project Purpose: Based on the actual prescription data of traditional Chinese medicine provided by the hospital, construct a recommendation system for prescription generation, with input as disease symptoms and output as relevant prescription drugs
  * Clean and organize the data of traditional Chinese medicine prescriptions and medical records provided by the hospital
  * Utilizing **Bayes Classifier Chain(multi-label classification)** combined with **Cost-Sensitive SVM** method to construct a drug recommendation  system based on text data of traditional Chinese medicine prescriptions
  * Using the **Transformer** module proposed by Google and an **end-to-end machine translation** model, a traditional Chinese medicine prescription recommendation system is constructed using a question and answer system approach
* **Research on Cell Pathways Related to Prostate Cancer**
  * PI: Yao Li
  * Life Science School of Fudan University
  * Using experimental methods to study the regulatory pathways of long non coding RNA(lnc RNA) that may be involved in prostate cancer
  * Mainly participated in the preliminary literature research and experimental part (western blot, Rt-PCR)
  
Skills
======
* **Programming**
  * C++: multi-threading programing, performance optimization
  * Python: pytorch, tensorflow
  * High performance computing: cuda, TensorRT, TVM
  * Linux
* **Algorithm**
  * Machine Learning
  * Deep Learning: CNN, RNN, Transformer, Bert
* **Compute Biology**
  * GROMACS, pymol
* **English**
  * CET-6 : 498 (2017-6)

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
  
<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
