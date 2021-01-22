---
title: [Home of Only1chunts](https://only1chunts.github.io/)
tags: home
date: 2020-01-01

---
{% include header.html %}

https://only1chunts.github.io/  

[And Bang the dirt is gone!](pages/bang.md)

My [CV](pages/my-cv.md)

My first [post](pages/my-first-post.md)
and a new [one](_posts/2021-01-021-readme.md)

change line
{% for tag in tags %}
	<a href="{{ tag | slugify }}"> {{ tag }} </a>
{% endfor %}

add another new line



insert
  <ul>
    {% for post in site.categories.news %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>


{% for category in site.categories %}
  <h3>{{ category[0] }}</h3>
  <ul>
    {% for post in category[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}

put some space here
<ui>
  {% for post in site.posts %}
	{% assign excerptParts = post.excerpt | split: "<!-- excerpt-start -->" %}
    {{ excerptParts[1] | strip_newlines | truncatewords: 50 }}
     {{ post.date | date: "%-d %B %Y" }} <a href="{{ post.url }}">{{ excerptParts[1] }} </a>
        <br>
  {% endfor %}
</ui>

change some text after.

{% raw %}

---
layout: default
title: New board members
category: news
tag: [news , board]
date: 2018-05-07
---

{% endraw %}
