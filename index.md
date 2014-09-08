---
layout: page
title: iPass ACE Exam
#tagline: blogging changes to the Adobe ACE exam landscape
header: Welcome to iPass-ACE-Exam
image: road.jpg
---
{% include JB/setup %}

This site is dedicated to information relating to the Adobe ACE Exams.  While there are a wide selection of <a href="http://www.pearsonvue.com/adobe/exams" target="_blank" rel="external">exams to choose from</a>, we aim to cover the following:

- [Adobe Photoshop Exam](/tags.html#Photoshop-ref)
- [Adobe Illustrator Exam](/tags.html#Illustrator-ref)
- [Adobe InDesign Exam](/tags.html#InDesign-ref)
- [Adobe DreamWeaver Exam](/tags.html#DreamWeaver-ref)
- [Adobe Flash Exam](/tags.html#Flash-ref)
- [Adobe Acrobat Exam](/tags.html#Acrobat-ref)

Would you like to write an article for us?  If you’re sitting or have recently sat any of the Adobe ACE exams, <a href="https://www.ipassexam.com/contact?subject=iPass-ACE-Exam%20Article-Idea&message=" target="_blank" ref="external">we’d love to hear about your experience</a>. 

[Visit our archive](/archive.html) to view a full lists of articles.

<hr />

Recent Articles:
----------------


<ul class="list-group" style="margin-top: 15px;">
  {% for post in site.posts %}
    <li class="list-group-item">
    	<span class="badge pull-right">{{ post.date | date_to_string }}</span> <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>



