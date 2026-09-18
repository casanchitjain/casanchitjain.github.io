---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Academic Positions

- **Assistant Professor**, Ahmedabad University (July 2026–present)

## Education

- **Indian Institute of Management Bangalore**  
  PhD in Finance and Accounting, 2021–2026

- **Institute of Chartered Accountants of India**  
  Chartered Accountant, 2017

- **CFA Institute**  
  Completed CFA Level I, 2018

- **Ahmedabad University**  
  Bachelor of Commerce, 2014

Corporate experience
======

- Senior Product Manager, Wealth, Batlivala & Karani (2019–2021)
- Product Specialist, ICICI Prudential Asset Management Company (2017–2019)
- Transaction Advisory Analyst, Corporate Catalyst India (2015–2016)

Outreach & Financial Education
======

- Personal Finance Trainer, Finance ke Funde Academy (2018–present) — pro-bono personal finance workshops and training sessions
- Mutual Funds Product Training Sessions, ICICI Prudential AMC (2017–2019)
- Academic/Career Counselor, Institute of Chartered Accountants of India (2017–present)

  
Skills
======
### Programming
- R
- Python
- LaTeX

### Databases
- CRSP
- Compustat
- CMIE Prowess
- PRIME Mutual Funds
- Morningstar
- Bloomberg

### Languages
- English
- Hindi
- Gujarati (elementary)


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% if post.category != 'working' %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>

Working Papers
======
  <ul>{% for post in site.publications reversed %}
    {% if post.category == 'working' %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>
  
Talks
======

- Financial Wellness Program, Swiss Consulate, Bangalore (Jan–Jun 2024) — [Letter of appreciation](/files/letter-swiss-consulate-2024.pdf)

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
