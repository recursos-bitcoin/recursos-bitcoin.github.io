---
layout: resources
title: Libros sobre Bitcoin
image: /assets/images/bitcoin-resources-twitter-cover.png
description: Libros selectos sobre Bitcoin.
---

La siguiente es una lista incompleta de libros sobre Bitcoin que vale la pena leer. Algunos de los
libros listados a continuación fueron discutidos en el [Bitcoiner Book
Club](https://www.youtube.com/playlist?list=PL8GxRkxnvMl3_O3DYNQJFnVBvvt8A9qqW)
organizado por John Vallis.

Dirígete a la [tabla de contenidos](#toc) para obtener un resumen de las distintas secciones.

---

<center>
  <p><small><a href="#toc">↓ Tabla de contenidos ↓</a></small></p>
</center>

---

{% assign sorted_categories = site.categories | sort: 'order' %}

{% for cat in sorted_categories %}

## {{ cat.title }}

{% capture my_include %}{% include category-{{ cat.short }}.md %}{% endcapture %}
{{ my_include | markdownify }}


{% if cat.short=="non-technical" %}
{% include books.html category=cat.short above_the_fold=1 %}
{% include books.html category=cat.short above_the_fold=2 %}
{% else %}
{% include books.html category=cat.short above_the_fold=true %}
{% endif %}


[Ver todos los libros en {{ cat.title }} »]({{ cat.url }})

{% endfor %}

---

## Lista de todos los libros

Para los fanáticos de CTRL+F.

Asegúrate también de consultar [bitcoiner books](https://www.bitcoinerbooks.com/)
y la [lista de grandes libros de JBP](https://www.jordanbpeterson.com/great-books/).

{% include books-list.html %}

[Ver muro de libros »][books-wall]

[books-wall]: {{ '/books/wall' | absolute_url }}

---

[« volver al índice][index]

[index]: {{ '/books' | absolute_url }}

{% include bibliography.md %}
