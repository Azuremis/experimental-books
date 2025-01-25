---
layout: page
title: Books
permalink: /books/
---

# Experimental Books

A collection of books exploring consciousness, spirituality, and the nature of reality.

{% for book in site.books %}
## [{{ book.title }}]({{ site.baseurl }}{{ book.url }})
{{ book.description }}

[Read Book]({{ site.baseurl }}{{ book.url }}) | 
[View Changelog]({{ site.baseurl }}{{ book.url }}changelog) | 
[View Roadmap]({{ site.baseurl }}{{ book.url }}roadmap)

---
{% endfor %} 