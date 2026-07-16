---
title: "数理统计"
permalink: /math-statistics/
layout: single
toc: true
---

{% for file in site.static_files %}
{% if file.path contains "/pdfs/shuli-tongji/" and file.extname == ".pdf" %}
- [{{ file.basename | replace: "_", " " }}]({{ file.path }})
{% endif %}
{% endfor %}
