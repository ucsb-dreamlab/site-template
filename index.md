<div class="posts">
{% for post in site.posts %}
<h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
<small>{{ post.date | date: "%-d %B %Y" }}</small>
{% if post.description %}
  <p class="view">{{ post.description }}</p>
{% endif %}
{% endfor %}
</div>
