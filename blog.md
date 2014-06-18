---
layout: default
permalink: /blog/
class: blog
---
<h1>Blog</h1>

<ul class='tags'>
	<li><a href='#tag-all' class='tag-all' data-active='true'>All</a>
	{% for tag in site.tags %}
	<li><a href='#tag-{{ tag[0] | replace:' ','-' | downcase }}' class='tag-{{ tag[0] | replace:' ','-' | downcase }}'>{{ tag[0] }} <span>x{{ tag[1].size }}</span></a>
	{% endfor %}
</ul>

{% for post in site.posts %}
<div class='blog__item{% for tag in post.tags %} tag-{{ tag | replace:' ','-' | downcase }}{% endfor %}' >
	<p class='date'>{{ post.date | date: "%b. %e, %Y" }}
	<h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
</div>
{% endfor %}