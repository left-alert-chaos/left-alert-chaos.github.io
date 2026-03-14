# Blog
All my posts, newest to oldest.

<ul>
{% for post in site.posts %}
	<div class="post-preview">
		<a href="{{ post.url }}">{{ post.title }}</a>
		<p>{{ post.date }}</p>
		<p>{{ post.excerpt }}</p>
	</div>
{% endfor %}
</ul>

Credit: Some of the HTML to display the posts came from [this documentation page.](https://jekyllrb.com/docs/posts/)