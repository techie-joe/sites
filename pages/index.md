# Pages

Number of pages in this site: {{ site.pages.size | default:0 }}

{% for page in site.pages %}
### [{{ page.title }}]({{ page.url }})
path      : {{ page.path }}
published : {{ page.published }}
{% endfor %}
