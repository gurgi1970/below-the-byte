---
layout: none
title: Latest Post
permalink: /latest/
---

{% assign latest_post = site.posts | first %}
<meta http-equiv="refresh" content="0; url={{ latest_post.url | relative_url }}" />
