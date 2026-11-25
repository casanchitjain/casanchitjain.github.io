---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

I study how regulation and organizational structure shape the behavior of mutual funds, business groups, and investors in India, using quasi-experimental methods and large-scale text analysis. My work has three themes:

- **Regulatory design and investor welfare:** how SEBI rules affect fund managers, distributors, and retail investors.
- **Information transmission in organizational networks:** how financing decisions and disclosures spill over across affiliated firms.
- **Computational text analysis in finance:** using language models to extract structure from news, legal judgments, and regulatory disclosures.

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
