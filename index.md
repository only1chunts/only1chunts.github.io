https://only1chunts.github.io/  

[And Bang the dirt is gone!](pages/bang.md)

My [CV](pages/my-cv.md)

My first [post](pages/my-first-post.md)
and a new [one](_posts/2021-01-021-readme.md)

put some space here

<ul>
  {% for post in site.posts  limit:2 %}
    <tr>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
      {{ post.date | date: "%B %e, %Y" }}
      <br>
    </tr>
  {% endfor %}
</ul>

and add some text after.
