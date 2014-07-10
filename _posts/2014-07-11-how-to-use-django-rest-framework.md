---
layout: post
title: "How to Use Django Rest Framework?"
description: ""
category: 
tags: [django, REST, API]
---
{% include JB/setup %}

<a href="">Django-Rest-Framework</a> is one of the awesome of library helps you to build API's

### Installation



    1. pip install djangorestframework

    2.  INSTALLED_APPS = (
         ...
         'rest_framework',
         )

3. Create a Serializer.py inside your app
<script src="https://gist.github.com/shashisp/091910b85117f0979238.js"></script>

3.urls.py

<script src="https://gist.github.com/shashisp/c50c795d4b76e1fb0794.js"></script>


4.views.py looks like this 
<script src="https://gist.github.com/shashisp/01d679764dd2c2160f5f.js"></script>


That's you're done! you can browse your services at /api

Happy Hacking! :)
 
