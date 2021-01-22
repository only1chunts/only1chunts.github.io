https://only1chunts.github.io/  

[And Bang the dirt is gone!](pages/bang.md)

My [CV](pages/my-cv.md)

My first [post](pages/my-first-post.md)
and a new [one](_posts/2021-01-021-readme.md)

insert
  <ul>
    {% for post in site.category.news %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
insert

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
     {{ post.date | date: "%-d %B %Y" }} <a href="{{ post.url }}">{{ post.excerpt }} </a>
        <br>
  {% endfor %}
</ui>

and add some text after.
