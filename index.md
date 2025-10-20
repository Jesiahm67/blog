Hi my name is Jesiah and this is The blog of tomorrow



<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
    <li>
      <a href="https://github.com/Jesiahm67/blog/commit/2f26a7fae892b839cb3a16989eb0614edd0651d4">Blog 1</a>
    </li>
  {% endfor %}
</ul>