---
layout: page
title: Testing Formkeep
excerpt: "An archive of articles sorted by date."
search_omit: true
---

<form accept-charset="UTF-8" action="https://formkeep.com/f/608e3a01b650" method="POST">
	<input type="hidden" name="utf8" value="✓"><br>
	<input type="email" name="email" placeholder="Your Email"><br>
	<input type="text" name="full_name" placeholder="Your Name"><br>
	<input type="url" name="website" placeholder="Your Website"><br>
	<button type="submit">Submit</button>
</form>

<!--
<ul class="post-list">
{% for post in site.categories.articles %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt | remove: '<p>' | remove: '</p>' }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>-->
