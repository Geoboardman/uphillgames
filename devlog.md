---
layout: default
title: Devlog
permalink: /devlog/
---

# 🛠 Devlog

Progress updates as we build our GPS-based games.

---

{% for post in site.posts %}

- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%B %d, %Y" }}
  {% endfor %}
