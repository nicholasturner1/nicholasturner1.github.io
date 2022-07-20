---
layout: page
title: Research
permalink: /research/
---

<img align="center" src="{{site.url}}/assets/mito_full_cell.png">
#### Selected publications
<ul class="posts">
{% for post in site.tags.research limit: 20 %}
  <div class="post_info">
   <li>
    {{ post.citation }}
   <a href="{{ post.paperlink }}">({{ post.journal }})</a>
   <br>{{ post.title }}
   <br><br>
   </li>
  </div>
{% endfor %}
</ul>
