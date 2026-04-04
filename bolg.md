---
layout: default
title: Blog
---

# 📝 Blog

{% for post in site.posts %}

## 🔹 [{{ post.title }}]({{ post.url }})

📅 {{ post.date | date: "%B %d, %Y" }}

{% if site.show_excerpts %}
{{ post.excerpt }}
{% endif %}

---

{% endfor %}
