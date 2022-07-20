---
layout: page
title: Code
permalink: /code/
---

<center>
<img align="center" src="{{site.url}}/assets/synapses.png" width="70%">
</center>
<ul class="posts">
{% for post in site.tags.code limit: 20 %}
  <div class="post_info">
    <li>
<!--         <a href="{{ post.url }}">{{ post.title }}</a> -->
         {{ post.title }}
         <a href="{{ post.repourl }}">[repo]</a>
         <span>({{ post.daterange }})</span>
         <br> {{ post.description }}
         <br><br>
    </li>
    </div>
  {% endfor %}
</ul>
