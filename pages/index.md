# Posts and Pages

### Pages
{% for page in site.pages %}{% if page.title %}- [{{ page.title }}]({{ site.github.url }}{{ page.url }})
{% else %}- [{{ page.path }}]({{ site.github.url }}{{ page.url }})
{% endif %}{% endfor %}

### Posts
{% for post in site.posts %}{% if post.title %}- [{{ post.title }}]({{ site.github.url }}{{ post.url }})
{% else %}- [(Untitled post)]({{ site.github.url }}{{ post.url }})
{% endif %}{% endfor %}
