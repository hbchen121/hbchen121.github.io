---
layout:     post   				                 # 使用的布局（不需要改）
title:      Hello, Haobo 				         # 标题
published:  true                         # 是否发表（即网站上是否可见）
subtitle:   I'm Haobo Chen, nice to meet you.        #副标题
date:       2021-04-28 			               # 时间
author:     haobo chen 						         # 作者
header-img: img/blog_images.jpg 	         #这篇文章标题背景图片
catalog: true 						                 # 是否归档
tags:								                       #标签
    - Template
excerpt: emplate
---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
## Hey
> Blog Template

This is my first Blog, also the template of Blogs.
