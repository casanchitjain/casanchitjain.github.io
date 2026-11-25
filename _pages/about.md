---
permalink: /
title: "Sanchit Jain"
layout: home
tagline: "Assistant Professor of Finance, Ahmedabad University.<br>PhD, IIM Bangalore. Chartered Accountant."
redirect_from:
  - /about/
  - /about.html
---

I study how regulation and organisational structure shape the behaviour of mutual funds, business groups and investors in India, using quasi-experimental methods and large-scale text analysis. Before academia, I worked in asset and wealth management at ICICI Prudential Asset Management Company and Batlivala & Karani.

## Selected research

{% for post in site.publications reversed %}{% if post.selected %}
  {% include archive-single.html show_excerpt=false show_citation=false show_links=false show_abstract=true %}
{% endif %}{% endfor %}

[All research →](/research/)

## Teaching

<div class="cards">
{% assign courses = site.teaching | sort: "date" | reverse %}{% for c in courses limit:2 %}
  <a class="card" href="{{ c.url }}"><b>{{ c.title }}</b><span>{{ c.type }}, {{ c.venue }} · {{ c.date | date: "%Y" }}</span></a>
{% endfor %}
</div>

[All teaching →](/teaching/)
