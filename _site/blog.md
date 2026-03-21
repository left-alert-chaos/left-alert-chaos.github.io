# Blog
All my posts, newest to oldest.

<div class="posts-container">
{% for post in site.posts %}
	<div class="post-preview">
		<h1><a href="{{ post.url }}">{{ post.title }}</a></h1>
		<p>{{ post.date }}</p>
		<p>{{ post.excerpt }}</p>
	</div>
{% endfor %}
<div>