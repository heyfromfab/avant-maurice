# A vendre :

{% for post in site.posts %}
 {% if !post.sold %}
  ![{{ post.title }}]({{ site.baseurl }}/assets/{{ post.permalink }}.png)
 {% endif %}
{% endfor %}
