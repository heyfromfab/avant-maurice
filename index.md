---
title: index
---
# A vendre :

{% for post in site.posts %}{% if post.sold != true %}<a href="{{ site.baseurl }}{{ post.url }}"><img src="{{ site.baseurl }}/assets/{{ post.permalink }}.png" width="200"/></a>{% endif %} {% endfor %}
