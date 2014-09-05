---
layout: page
title: iPass ACE Exam
#tagline: blogging changes to the Adobe ACE exam landscape
image: road.jpg
---
{% include JB/setup %}

Welcome to iPass-ACE-Exam 

<ul class="list-group">
  {% for post in site.posts %}
    <li class="list-group-item">
    	<span class="badge pull-right">{{ post.date | date_to_string }}</span> <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>



