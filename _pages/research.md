---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research examines how institutional design shapes the behaviour of firms, intermediaries, and investors in financial markets, with a particular focus on India. I study questions in corporate finance, financial intermediation, and regulatory design using event studies, difference-in-differences designs, quasi-natural experiments, panel regressions, and AI-assisted text analysis.

The unifying question in my work is: How does the institutional environment affect economic decisions, and what are the consequences for market efficiency and investor welfare?

## Future Research Agenda

My future research focuses on three broad themes:

1. **Regulatory Design and Investor Welfare**  
   Examining how regulatory interventions by SEBI affect fund managers, distributors, and retail investors.

2. **Information Transmission in Organizational Networks**  
   Studying how financing decisions and disclosures generate spillover effects across affiliated firms.

3. **AI-Assisted Text Analysis in Finance**  
   Using large language models to extract structured information from financial news, legal judgments, and regulatory disclosures.


{% include base_path %}

<!-- Render publications by category, suppress abstracts, citations, and links -->
{% if site.publication_category %}
  {% for category in site.publication_category %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2>
        <hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html show_excerpt=false show_citation=false show_links=false %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html show_excerpt=false show_citation=false show_links=false %}
  {% endfor %}
{% endif %}
