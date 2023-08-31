---
layout: default
title: Accueil
---

# Bienvenue sur Mon Blog Jekyll !

Ceci est la page d'accueil de mon blog. Voici quelques articles récents :

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})
{{ post.excerpt }}
{% endfor %}

