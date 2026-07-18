---
layout: home
title: Kre8on Blog
---
# Kre8on Blog

AI visibility tracking, **Answer Engine Optimization (AEO)** and **Generative Engine Optimization (GEO)** — practical notes from the team at [Kre8on](https://kre8on.com/).

{% assign posts = site.pages | where: "dir", "/posts/" | sort: "name" | reverse %}
{% for p in posts %}
- [{{ p.name | replace: '.md','' | replace: '-',' ' | truncate: 70 }}]({{ p.url }}){% endfor %}

> Visit [kre8on.com](https://kre8on.com/) to track + grow your brand's visibility across ChatGPT, Claude, Gemini and Perplexity.
