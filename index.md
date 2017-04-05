---
title: index
---
# A vendre :

{% for post in site.posts %}{% if post.sold != true %}<span class="to-sell-photo-list">[![{{ post.title }}]({{ site.baseurl }}/assets/{{ post.permalink }}.png)]({{ site.baseurl }}{{ post.url }})</span>{% endif %} {% endfor %}
