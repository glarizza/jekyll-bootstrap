---
layout: page
title: I'm too lazy to manage a blog
tagline: 
---
{% include JB/setup %}


## Obviously, this isn't complete...

## Sample Posts

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


