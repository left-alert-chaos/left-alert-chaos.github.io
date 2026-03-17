# Blog
All my posts, newest to oldest.

<div>
{% for post in site.posts %}
	<div class="post-preview">
		<a href="{{ post.url }}">{{ post.title }}</a>
		<p>{{ post.date }}</p>
		<p>{{ post.excerpt }}</p>
	</div>
{% endfor %}
<div>