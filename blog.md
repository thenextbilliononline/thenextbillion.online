---
layout: meta
permalink: /blog
---
# The Next Billion Online Blog
#### Index of blogs
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
