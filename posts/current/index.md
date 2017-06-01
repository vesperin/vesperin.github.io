---
layout: default
title: Current projects
---

{% for post in site.categories.current %}

- [**{{ post.title }}**]({{ post.url }}) {{ post.description | strip_html }}

{% endfor %}