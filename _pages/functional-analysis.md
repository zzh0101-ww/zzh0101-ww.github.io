---
title: "泛函分析"
permalink: /functional-analysis/
layout: single
toc: true
---

{% for file in site.static_files %}
{% if file.path contains "/pdfs/fanhan-fenxi/" and file.extname == ".pdf" %}
- [{{ file.basename | replace: "_", " " }}]({{ file.path }})
{% endif %}
{% endfor %}
