# jandumke.github.io


https://jekyllrb.com/docs/pages/

https://jekyllrb.com/docs/posts/


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
