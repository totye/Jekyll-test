---
layout: default
title: 随笔
---


  <ul>
    {% for post in site.posts %}
      <li>
      	<a href="{{ site.baseurl }}{{ post.url }}">
      		<span>{{ post.title }}</span>
	      	<span>{{ post.date | date: "%Y年%m月%d日" }}</span> 
      	</a>
      </li>
    {% endfor %}
  </ul>
