---
layout: page
title: Research
permalink: /research/
---

#### Selected publications
<ul class="posts">
{% for post in site.tags.research limit: 20 %}
  <div class="post_info">
    <li>
<!--         <a href="{{ post.url }}">{{ post.citation }}</a> -->
         {{ post.citation }}
         <a href="{{ post.paperlink }}">[paper]</a>
         <br>{{ post.title }}
         <br><br>
    </li>
    </div>
  {% endfor %}
</ul>
