# Pages

{% for page in site.pages %}{% if page.title %}- [{{ page.title }}]({{ page.url }})
{% else %}- [{{ page.path }}]({{ page.url }})
{% endif %}{% endfor %}
