---
layout: default
title: Hello!
---


## Hi! I'm Jim. I write about stuff and make photos

Latest Posts: {% for post in site.posts limit:5 %}
   <article>
      {% include blog.html %}
    </article>
{% endfor %}

