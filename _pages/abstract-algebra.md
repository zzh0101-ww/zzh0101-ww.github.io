---
title: "抽象代数"
permalink: /abstract-algebra/
layout: single
toc: true
---

{% for file in site.static_files %}
{% if file.path contains "/pdfs/chouxiang-daishu/" and file.extname == ".pdf" %}
- [{{ file.basename | replace: "_", " " }}]({{ file.path }})
{% endif %}
{% endfor %}
