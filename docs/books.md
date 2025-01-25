---
layout: page
title: Books
permalink: /books/
---

# Experimental Books

A collection of books exploring consciousness, spirituality, and the nature of reality.

{% for book in site.books %}
## [{{ book.title }}]({{ book.url | relative_url }})
{{ book.description }}

[Read Book]({{ book.url | relative_url }}) | 
[View Changelog]({{ book.url | relative_url }}changelog) | 
[View Roadmap]({{ book.url | relative_url }}roadmap)

---
{% endfor %} 