LIST
====

{% assign pp = site.pages | sort_natural: "title" %}

{% for p in pp %}
1. [{{ p.title }} -]({{ p.url }})
{% endfor %}
