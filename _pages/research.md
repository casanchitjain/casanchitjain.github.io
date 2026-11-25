---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research examines how regulatory and organizational institutions shape the behavior of firms, financial intermediaries, and investors, with a particular focus on India. My primary research area is mutual funds and delegated asset management. I study how compensation structures, distribution incentives, and regulatory interventions affect capital allocation and investor welfare. More broadly, I work in corporate finance, financial intermediation, and law and finance using quasi-experimental methods, panel regressions, and computational text analysis. The central question in my work is how institutional design influences economic decisions and, in turn, affects market efficiency and investor welfare.

My current and future research focuses on three broad themes:

1. **Regulatory Design and Investor Welfare**  
   Examining how SEBI regulations affect mutual fund managers, distributors, and retail investors.

2. **Information Transmission in Organizational Networks**  
   Studying how financing decisions, disclosures, and legal institutions generate spillover effects across affiliated firms and markets.

3. **Computational Text Analysis in Finance**  
   Using large language models to extract structured information from financial news, legal judgments, and regulatory disclosures.

{% include base_path %}

<!-- One collapsible section per category; only one open at a time (details name= makes an exclusive group) -->
{% assign opened = false %}
{% for category in site.publication_category %}
{% assign items = site.publications | where: "category", category[0] | reverse %}
{% if items.size > 0 %}
<details class="research-section" name="research-sections"{% unless opened %} open{% assign opened = true %}{% endunless %}>
<summary>{{ category[1].title }} <span class="research-count">{{ items.size }}</span></summary>
{% for post in items %}
{% include archive-single.html show_excerpt=false show_citation=false show_links=false show_abstract=true show_conferences=true show_order=true %}
{% endfor %}
</details>
{% endif %}
{% endfor %}
