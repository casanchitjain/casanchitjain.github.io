---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

My teaching philosophy centers on simplifying complex ideas through storytelling, real-world analogies, and practical applications. I aim to help students understand the economic intuition behind financial concepts and connect theory to current developments in financial markets and regulation.

## Teaching Philosophy

I use active learning methods including:
- Problem sets
- Short cases
- Data exercises
- Discussion of current market events

My industry experience in asset management and wealth management allows me to connect classroom concepts to real-world investment decisions and regulatory developments. I also integrate AI tools such as ChatGPT and NotebookLM into teaching where appropriate to help students analyze large bodies of financial and legal text.

## Courses 

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
