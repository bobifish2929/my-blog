---
layout: default
title: Главная
---

# Мой блог об ИИ

Здесь я пишу о технологиях, которые меняют мир — искусственный интеллект, роботы и будущее.

---

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url | relative_url }})
*{{ post.date | date: "%d %B %Y" }}*

{{ post.excerpt }}

---
{% endfor %}
