---
layout: page
title: 小六
tagline: "代码写得少，别骗我"
---
{% include JB/setup %}

## 叼叼的

**文章列表**
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

---

## 参考学习

<ul>
<li> 
<a href="http://jekyllrb.com/">Jekyll</a>
</li>
<li>
<a href="http://github.com/plusjade/jekyll-bootstrap">Jekyll Bootstrap</a>
</li>
<li>
<a href="http://www.cnblogs.com/BeginMan/p/3549235.html">搭建 GitHub Pages by jekyll</a>
</li>
</ul>


