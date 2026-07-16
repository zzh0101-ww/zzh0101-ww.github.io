---
title: "数学物理方程"
permalink: /math-physics-equation/
layout: single
toc: true
---

{% for file in site.static_files %}
{% if file.path contains "/pdfs/shuxue-wuli-fangcheng/" and file.extname == ".pdf" %}
- [{{ file.basename | replace: "_", " " }}]({{ file.path }})
{% endif %}
{% endfor %}
