<div class="post-list">
{% for post in site.posts %}
<small>{{ post.date | date: "%-d %B %Y" }}</small>
<h1><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h1>
{% if post.description %}
  <p class="view">{{ post.description }}</p>
{% endif %}
{% endfor %}
</div>
