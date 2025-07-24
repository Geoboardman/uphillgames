---
layout: default
title: Devlog
permalink: /devlog/
---

# 🛠 Devlog

Progress updates as we build our GPS-based games.

---

{% for post in site.posts %}

<div class="mb-12 pb-8 border-b border-gray-700">
  <h2 class="text-2xl font-semibold text-blue-400">{{ post.title }}</h2>
  <p class="text-sm text-gray-400 mb-4">{{ post.date | date: "%B %d, %Y" }}</p>
  <div class="prose prose-invert max-w-none">
    {{ post.content }}
  </div>
</div>
{% endfor %}
