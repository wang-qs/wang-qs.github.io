

# All My Post

{% for post in site.posts | sort_by: "title" %}
[ {{ post.title }} ]( {{ post.url }} )
{% endfor %}

