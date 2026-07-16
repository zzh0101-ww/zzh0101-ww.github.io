---
title: "高等代数"
permalink: /advanced-algebra/
layout: single
toc: true
---

{% for file in site.static_files %}
{% if file.path contains "/pdfs/gaodeng-daishu/" and file.extname == ".pdf" %}
- [{{ file.basename | replace: "_", " " }}]({{ file.path }})
{% endif %}
{% endfor %}
