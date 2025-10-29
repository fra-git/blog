---
layout: page
title: Blog
permalink: /posts/
---

# ✍️ I Miei Articoli Tecnici

Qui trovi l'elenco completo dei miei post:

---

{% for post in site.posts %}
- **[{{ post.title }}]({{ site.baseurl }}{{ post.url }})** - *{{ post.date | date_to_string }}*
{% endfor %}
