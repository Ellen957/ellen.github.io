---
layout: post-list
title: All Posts
excerpt: "A List of Posts"
comments: false
---
<meta charset="utf-8">
<head>
<body>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
	这是我在这个博客下的第一个文字，纪念一下。
</body>
</heand>