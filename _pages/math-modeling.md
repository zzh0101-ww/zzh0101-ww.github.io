---
title: "数学建模"
permalink: /math-modeling/
layout: single
toc: true
---

{% for file in site.static_files %}
{% if file.path contains "/pdfs/shuxue-jianmo/" and file.extname == ".pdf" %}
- [{{ file.basename | replace: "_", " " }}]({{ file.path }})
{% endif %}
{% endfor %}
