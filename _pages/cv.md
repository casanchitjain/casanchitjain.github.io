---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<details class="research-section" open markdown="1">
<summary>Academic Positions</summary>
- **Assistant Professor**, Ahmedabad University (July 2026–present)

</details>

<details class="research-section" open markdown="1">
<summary>Education</summary>
<ol class="timeline">
  <li><span class="timeline__date">2021 – 2026</span><span class="timeline__body"><strong>PhD in Finance and Accounting</strong><br>Indian Institute of Management Bangalore</span></li>
  <li><span class="timeline__date">2018</span><span class="timeline__body"><strong>Completed CFA Level I</strong><br>CFA Institute</span></li>
  <li><span class="timeline__date">2017</span><span class="timeline__body"><strong>Chartered Accountant</strong><br>Institute of Chartered Accountants of India</span></li>
  <li><span class="timeline__date">2014</span><span class="timeline__body"><strong>Bachelor of Commerce</strong><br>Ahmedabad University</span></li>
</ol>

</details>

<details class="research-section" markdown="1">
<summary>Corporate experience</summary>
<ol class="timeline">
  <li><span class="timeline__date">May 2019 – Jun 2021</span><span class="timeline__body"><strong>Senior Product Manager, Wealth</strong><br>Batlivala &amp; Karani</span></li>
  <li><span class="timeline__date">Sep 2017 – May 2019</span><span class="timeline__body"><strong>Product Specialist</strong><br>ICICI Prudential Asset Management Company</span></li>
  <li><span class="timeline__date">Sep 2015 – Feb 2016</span><span class="timeline__body"><strong>Transaction Advisory Analyst</strong><br>Corporate Catalyst India</span></li>
  <li><span class="timeline__date">Aug 2013 – Sep 2015</span><span class="timeline__body"><strong>Article Assistant, Assurance</strong><br>ASA &amp; Associates LLP</span></li>
  <li><span class="timeline__date">Aug 2012 – Aug 2013</span><span class="timeline__body"><strong>Article Assistant, Assurance</strong><br>S.R. Batliboi &amp; Associates LLP (EY)</span></li>
</ol>

</details>

<details class="research-section" markdown="1">
<summary>Scholarships & Awards</summary>
<ol class="timeline">
  <li><span class="timeline__date">Sep 2026</span><span class="timeline__body"><strong>Content Award</strong><br>FinX Institute (CIEL)</span></li>
  <li><span class="timeline__date">2025 – 26</span><span class="timeline__body"><strong>Florintree Scholarship Award</strong><br>IIM Bangalore</span></li>
  <li><span class="timeline__date">Jun 2025</span><span class="timeline__body"><strong>Best Research Paper Award in Finance, First Prize, Corporate Finance</strong><br>RSFE Conference</span></li>
  <li><span class="timeline__date">2024 – 25</span><span class="timeline__body"><strong>Mirae Asset Scholar Award</strong><br>IIM Bangalore</span></li>
  <li><span class="timeline__date">Apr 2018</span><span class="timeline__body"><strong>Stunning Debutant Award</strong><br>ICICI Prudential AMC Ltd</span></li>
</ol>

</details>

<details class="research-section" markdown="1">
<summary>Professional Service</summary>
- Discussant: RSFE 2025
- Conference Reviewer: ICGS Conference 2024
- Case Reviewer: Asian Journal of Management Cases (Nov 2026)
- Faculty Mentor, Capstone Projects (2026–27, ongoing), Amrut Mody School of Management, Ahmedabad University:
  - *AI-Driven Commodity and Purchase-Timing Intelligence for Manufacturing Procurement*
  - *From Traditional Stockbroking to Digital Investment Apps: Investor Behaviour in India*

</details>

<details class="research-section" markdown="1">
<summary>Outreach & Financial Education</summary>
- Financial Wellness Program Facilitator, Switzerland Consulate, Bangalore (Jan–Jun 2024) — pro-bono workshops for support staff — [Letter of appreciation](/files/letter-swiss-consulate-2024.pdf)
- Personal Finance Training, Finance ke Funde Academy (2018–present) — pro-bono personal finance workshops
- Mutual Funds Product Training Sessions, ICICI Prudential AMC (2017–2019)
- Academic/Career Counselor, Institute of Chartered Accountants of India (2017–present)

</details>

<details class="research-section" markdown="1">
<summary>Skills</summary>
- **Programming:** R, Python, LaTeX
- **Datasets:** CRSP, Compustat, CMIE Prowess, PRIME Mutual Funds, Morningstar, Bloomberg
- **Languages:** English, Hindi, Gujarati (elementary)

</details>

<details class="research-section" open markdown="1">
<summary>Publications</summary>
<ul>{% for post in site.publications reversed %}
    {% if post.category != 'working' %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>

</details>

<details class="research-section" markdown="1">
<summary>Working Papers</summary>
<ul>{% for post in site.publications reversed %}
    {% if post.category == 'working' %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>

</details>

<details class="research-section" markdown="1">
<summary>Invited Talks</summary>
<ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

</details>

<details class="research-section" markdown="1">
<summary>Teaching</summary>
<ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

- Valuation Lab (8-week workshop), Amrut Mody School of Management, Ahmedabad University (Oct–Dec 2026)
- Teaching Assistant, IIM Bangalore (Jun 2023 – Dec 2024): Accounting for Decisions (PGP I), Corporate Finance (PGP I), Fixed Income Securities & its Derivatives (PGP II)

</details>
