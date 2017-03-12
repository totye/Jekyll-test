---
layout: default
title: 随笔
---


  <ul>
    {% for post in site.posts %}
      <li>
      	<a href="{{ post.url }}">
      		<span>{{ post.title }}</span>
	      	<span>{{ post.date | date_to_string }}</span> 
      	</a>
      </li>
    {% endfor %}
  </ul>
