---
title: "傅里叶分析"
permalink: /fourier-analysis/
layout: single
toc: true
---

{% for file in site.static_files %}
{% if file.path contains "/pdfs/fuliye-fenxi/" and file.extname == ".pdf" %}
- [{{ file.basename | replace: "_", " " }}]({{ file.path }})
{% endif %}
{% endfor %}
