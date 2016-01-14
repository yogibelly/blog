---
layout: page
title: Testing Formspree
excerpt: "An archive of articles sorted by date."
search_omit: true
---

<form action="//formspree.io/sahirbhatnagar@gmail.com"
      method="POST">
    <input type="text" name="name" placeholder="Your Name *"><BR>
    <input type="email" name="_replyto" placeholder="Your Email *"><BR>
    <input type="submit" value="Send">
</form>

<!--
<ul class="post-list">
{% for post in site.categories.articles %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt | remove: '<p>' | remove: '</p>' }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>-->
