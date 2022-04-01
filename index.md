---
layout: ddefault
---

# Новости
* * *

{% for post in site.posts %}
> ### [{{ post.title }}]({{ post.url }}) (постирано на **{{ post.date | date: "%m.%d.%Y" }}**)
> ##### {{ post.description }}
{% endfor %}
