---
layout: default
title: Главная
---

# Мой блог

## Последние посты:

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%d.%m.%Y" }}*
{% endfor %}
