---
title: Posts
description: Posts on this site.
permalink: posts
---

# Posts

> {{ page.description }}

{% for p in site.posts %}{% if p.title %}- [{{ p.title }}]({{ site.github.url }}{{ p.url }})
{% else %}- [(Untitled post)]({{ site.github.url }}{{ p.url }})
{% endif %}{% endfor %}
