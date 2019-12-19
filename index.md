---
layout: no-style
---

{% include recipe-nav.html %}

# Family Recipes

{% assign pages = site.pages | sort: 'order' %}
{% for page in pages %}
{% if page.order <= 3 %}
- [{{ page.title }}]({{ page.url | relative_url }})
{% endif %}
{% endfor %}

