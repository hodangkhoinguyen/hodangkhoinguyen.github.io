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
* Ph.D. in Computer Science, George Mason University, 2029 (expected)
  * GPA: 3.9
* B.S. in Computer Science, University of California, Davis, 2023
  * GPA: 3.87

Experience
======
* Aug 2024 – Present: Research Assistant
  * George Mason University, Fairfax, VA
  * Advisor: Prof. ThanhVu Nguyen
  * Metamorphic testing of MILP solvers (Gurobi, SCIP, HiGHS, CBC, GLPK): 36 defects found, 26 previously unknown
  * GPU-accelerated bit-flip fault verifiers for quantized DNNs (OrBit, mBFV)
  * Contributor to NeuralSAT, ranked 2nd in VNN-COMP 2024 and 2025

* Aug 2024 – Present: Graduate Teaching Assistant
  * George Mason University, Fairfax, VA
  * CS 310: Data Structures (Java)

* Jun 2023 – Aug 2024: Software Developer
  * Department of Plant Pathology, University of California, Davis
  * Built and maintained [KitBase](https://kitbase.ucdavis.edu/), an open-access rice genomics platform (PHP, Drupal, MySQL)
  * Built Python and Perl pipelines to filter, annotate, and analyze genomic data for 3,268 mutant lines

Skills
======
* Languages: Python, C++, Java, TypeScript/JavaScript, SQL, PHP, Perl, Lean 4
* Frameworks and libraries: PyTorch, NumPy, Pandas, Next.js, React.js, Node.js, Express.js, tRPC, Spring Boot, Drupal
* Tools: Git, Docker, Linux, AWS, Azure, Supabase, MongoDB
* Research areas: metamorphic testing, formal and DNN verification, bound propagation, MILP/SMT, quantization

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
