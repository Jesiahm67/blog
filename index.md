Hi my name is Jesiah and this is The blog of tomorrow



<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
    <li>
      <a href="/blog/_posts/9-17-blog1.md">Blog 1</a>
    </li>
  {% endfor %}
</ul>