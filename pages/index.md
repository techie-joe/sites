# Pages

{% for page in site.pages %}{% if page.title %}- [{{ page.title }}]({{ site.github.url }}{{ page.url }})
{% else %}- [{{ page.path }}]({{ site.github.url }}{{ page.url }})
{% endif %}{% endfor %}
