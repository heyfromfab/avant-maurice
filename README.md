# A vendre :

{% for post in site.posts %}
![{{ post.title }}]({{ site.baseurl }}/assets/{{ post.permalink }}.png)  
{% endfor %}
