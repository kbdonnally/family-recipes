---
title: Recipe Index
nav-name: Recipe Index
layout: no-style
permalink: /recipe-index/
order: 3
---

{% include recipe-nav.html %}

<main markdown="1">

# Recipe Index

This will eventually hold a rolodex of all recipes.

## Sweet:

{% for sweet in site.sweet %}
- [{{ sweet.title }}]({{ sweet.url | relative_url }})
{% endfor %}

## Savory:

</main>

{% include recipe-footer.html %}