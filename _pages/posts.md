---
title: Recent Posts
layout: page
permalink: /posts/
---

<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>({{ post.date | date: "%b %-d, %Y" }})</small>
    </li>
  {% endfor %}
</ul>

[View All Posts]({{ site.baseurl }}/archive/)
