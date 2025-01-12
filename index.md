---
layout: default
---

<h1>{{ site.title }}</h1>
<p>{{ site.description }}</p>

<ul>
  {% for post in /posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
