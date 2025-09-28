LIST
====

{% assign pp = site.pages | sort_natural: "title" %}

{% for p in pp %}[___{{ p.title }}___]({{ p.url }}){% endfor %}
