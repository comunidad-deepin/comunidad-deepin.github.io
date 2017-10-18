---
layout: page
show_meta: false
title: "Lista de páginas relacionadas al manual"
subheadline: "Aprende a usar Deepin"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/manual/lista/"
---

Está categoría contiene publicaciones del manual de usuario.

<ul>
    {% for post in site.categories.manual %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>

Ir al [Archivo]({{ site.url }}/blog/archive/).