---
layout: page
title: Shashi Essp
tagline: just another Dreamer
---
{% include JB/setup %}

I'm Shashi Essp, a Computer Programmer from India, StartupKid, FOSS Enthusiast, Wannabe Enterprenuer,Traveller,a Python fan Boy and Nocturnal Creature :D 






blog posts.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-53320301-1', 'auto');
  ga('send', 'pageview');

</script>
