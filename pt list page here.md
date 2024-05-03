LIST
{% for p in site.pages | sort : "name" %}
- [{{ p.name }}]({{ p.url }})
{% endfor %}
