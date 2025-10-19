Hi my name is Jesiah and this is The blog of tomorrow



<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <a href="blog1">Blog 1</a>
    </li>
  {% endfor %}
<ul>
  <li>
    <a href="blog1">Blog 1</a>
  </li>
</ul>
</ul>