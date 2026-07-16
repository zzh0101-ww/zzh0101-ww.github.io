---
title: "现代几何基础"
permalink: /modern-geometry/
layout: single
toc: true
---

{% for file in site.static_files %}
{% if file.path contains "/pdfs/xiandai-jihe-jichu/" and file.extname == ".pdf" %}
- [{{ file.basename | replace: "_", " " }}]({{ file.path }})
{% endif %}
{% endfor %}
