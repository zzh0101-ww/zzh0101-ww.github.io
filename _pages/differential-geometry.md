---
title: "微分几何"
permalink: /differential-geometry/
layout: single
toc: true
---

{% for file in site.static_files %}
{% if file.path contains "/pdfs/weifen-jihe/" and file.extname == ".pdf" %}
- [{{ file.basename | replace: "_", " " }}]({{ file.path }})
{% endif %}
{% endfor %}
