LIST
====
ga.

{% for p in site.pages | sort_natural: "title" %}
<[{{ p.title }}}]({{ p.url }}).{{ p.who }>
{% endfor %}
