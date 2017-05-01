---
layout: default
title: Franchement c'est chaud !
tagline: Supporting tagline
---
{% include JB/setup %}

<div class="blog-index">  
  {% assign post = site.posts.first %}
  {% assign content = post.content %}
  {% include post_detail.html %}
</div>