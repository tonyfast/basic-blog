# basic blog

{% for post in site.posts %}<li>
* [{{ post.title }}]({{site.baseurl}}{{ post.url }})
{% endfor %}
