LIST
{% for p in site.pages %}
- [{{ p.name }}]({{ p.url }})
{% endfor %}
