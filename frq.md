---
layout: page
permalink: /frq/
title: All FRQ Solutions
tagline: A List of FRQ Solutions
category: [frq]
tags: [blog]
---

{% for post in site.categories[category_name] %}
    <li>{{ post.title }}</li>
{% endfor %}