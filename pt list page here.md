LIST
{% for p in site.pages | sort %}
- [{{ p.name }}]({{ p.url }})
{% endfor %}
