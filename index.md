---
layout: default
title: Home
---

# Hi There!

## Nice to see you.

Just testing some things.

[About page](https://craigkraft.github.io/about)

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
