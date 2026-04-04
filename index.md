---
layout: default
title: Home
---

# 👋 Hi, I'm Umar

My name is Umar, and I am currently studying **BS Computer Engineering** at UET Faisalabad.  
I live in Faisalabad and currently studing in second semester.
I have a strong interest in technology and continuously work on improving my skills.
---

## 🚀 Skills

- 🤖 Machine Learning (Basics)
- 🐍 Python
- 💻 C#
- 🎨 CSS
- ⚡ JavaScript
- 🧠 Problem Solving

---

## 📝 Latest Blog Posts

{% for post in site.posts %}

### 👉 [{{ post.title }}]({{ post.url }})

🗓 {{ post.date | date: "%d %b %Y" }}

{% if site.show_excerpts %}
> {{ post.excerpt }}
{% endif %}

---

{% endfor %}
