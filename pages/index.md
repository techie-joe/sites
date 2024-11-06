# Pages

{% for page in site.pages %}{% if page.title %}
### [{{ page.title }}]({{ page.url }})
path      : {{ page.path }}
published : {{ page.published }}
{% endfor %}{% endif %}
