# avant-maurice


[premier post]({{ site.baseurl }}{% post_url 2017-03-29-test %})
 
 {% for post in site.posts %}
coucou {{post.title}}
[{% post.title %}]({{ site.baseurl }}{{ post.url }})
  {% endfor %}

 
