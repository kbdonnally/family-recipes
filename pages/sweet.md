---
title: Sweet Recipes
nav-name: Sweet
layout: no-style
permalink: /sweet/
order: 2
---

{% include recipe-nav.html %}

<main class="sweet-recipe-wrapper" markdown="1">

# Sweet Recipes

{% assign sweets = site.sweet %}

{% for sweet in sweets %}
- [{{ sweet.title }}]({{ sweet.url | relative_url}})
{% endfor %}

</main>

{% include recipe-footer.html %}