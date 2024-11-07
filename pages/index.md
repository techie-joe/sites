---
title: Pages
description: Pages on this site.
permalink: pages
---

# Pages

{% for p in site.pages %}{% if p.title and p.title != page.title %}- [{{ p.title }}]({{ site.github.url }}{{ p.url }})
{% endif %}{% endfor %}
