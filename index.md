---
layout: page
title: Shashi Essp
tagline: just another Dreamer
---
{% include JB/setup %}

I'm Shashi Essp, a Computer Programmer from India, Startup and FOSS Enthusiast. 






older posts.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



