---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research examines how regulatory and organizational institutions shape the behavior of firms, intermediaries, and investors in financial markets, with a particular focus on India.

I study questions in corporate finance, financial intermediation, and regulatory design using quasi-experimental methods, panel regressions, and computational text analysis.

The central question in my work is how institutional arrangements influence economic decisions and, in turn, affect market efficiency and investor welfare.

## Research Agenda

My current and future research focuses on three broad themes:

1. **Regulatory Design and Investor Welfare**  
   Examining how interventions by SEBI affect mutual fund managers, distributors, and retail investors.

2. **Information Transmission in Organizational Networks**  
   Studying how financing decisions, disclosures, and regulatory actions generate spillover effects across affiliated firms.

3. **Computational Text Analysis in Finance**  
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
