---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
description: "Courses, teaching cases and teaching philosophy of Sanchit Jain, Assistant Professor of Finance at Ahmedabad University."
---

I teach finance by simplifying complex ideas through storytelling, real-world analogies, and practical applications, connecting theory to current developments in markets and regulation. Classes use problem sets, short cases, data exercises, and discussion of current events. Drawing on my industry experience in asset and wealth management, and on AI tools such as ChatGPT and NotebookLM for analyzing large bodies of financial and legal text, I connect classroom concepts to real investment decisions.

## Courses 

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}

## Teaching cases

{% for post in site.publications reversed %}{% if post.category == 'cases' %}
  {% include archive-single.html show_excerpt=false show_citation=false show_links=false %}
{% endif %}{% endfor %}

## Other teaching roles

<ul class="cv-entries">
  <li class="cv-entry"><span class="cv-entry__title cv-entry__title--plain">Valuation Lab (8-week workshop)</span><span class="cv-entry__meta">Amrut Mody School of Management, Ahmedabad University, Oct&ndash;Dec 2026</span></li>
  <li class="cv-entry"><span class="cv-entry__title cv-entry__title--plain">Teaching Assistant</span><span class="cv-entry__meta">Indian Institute of Management Bangalore, Jun 2023&ndash;Dec 2024: Accounting for Decisions (PGP I), Corporate Finance (PGP I), Fixed Income Securities &amp; its Derivatives (PGP II)</span></li>
</ul>
