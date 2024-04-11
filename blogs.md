---
layout: page
---

this will have a link to all my blogs.

all posts should be below.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

this should mark the end of all posts.