# Boucle simple sur les urls des posts
{% for post in site.posts %}
 [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}

# Boucle en lien avec les images
{% for post in site.posts %}
 ![{{ post.title }}]({{ site.baseurl }}/assets/{{ post.permalink }}.png)
{% endfor %}

