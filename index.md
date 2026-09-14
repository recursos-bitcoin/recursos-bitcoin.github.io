---
layout: resources
title: Recursos Bitcoin
image: /assets/images/bitcoin-resources-twitter-cover.png
description: Libros, articulos, podcasts y otros recursos selectos de Bitcoin.
redirect_from: resources
---

**Resumen para vagos:** Lee [El patrón Bitcoin][bitcoin-standard] y [La Tesis Alcista de Bitcoin][bullish-case-book].

---

## Esenciales

Para entender Bitcoin, tendrás que leer un libro o dos. Si solo quieres 
leer un libro, la mayoría de la gente recomendará **[El Patrón Bitcoin][the-bitcoin-standard]** 
de Saifedean Ammous, y con razón. Bitcoin es dinero, por lo que entender 
[La Ética De La Producción del Dinero][the-ethics-of-money-production] es fundamental para comprender
de qué trata Bitcoin. Si necesitas un curso intensivo en economía, lee [La Economía En Una Lección][economics-in-one-lesson] 
de Henry Hazlitt.

[economics-in-one-lesson]: {{ '/books/economics-in-one-lesson' | absolute_url }}
[the-bitcoin-standard]: {{ '/books/the-bitcoin-standard' | absolute_url }}
[the-ethics-of-money-production]: {{ '/books/the-ethics-of-money-production' | absolute_url }}
[bullish-case-book]: {{ '/books/the-bullish-case-for-bitcoin' | absolute_url }}

{% include books.html category='essentials' %}

[Ver todos los libros »][books]

Si prefieres una introducción más corta, lee y escucha lo siguiente:

- [La Tesis Alcista de Bitcoin][bullish-case-book] de Vijay Boyapati
- [The Stories We Tell About Money][aantonop-stories] de Andreas Antonopoulos

Además, cualquiera que se tome en serio entender Bitcoin debería comenzar por el principio y leer --o al menos hojear-- las 8 páginas que dieron origen a Bitcoin:

- [Bitcoin: A Peer-to-Peer Electronic Cash System][bitcoin-whitepaper] de Satoshi Nakamoto

Encuentra respuestas a preguntas frecuentes en las [Preguntas Frecuentes][faq].

[faq]: {{ '/faq' }}

---

<center>
  <p><small><a href="#toc">↓ Tabla de contenidos ↓</a></small></p>
</center>

[toc]: #toc
[essentials]: #essentials
[books]: #books
[articles]: #articles
[podcasts]: #podcasts
[episodes]: #podcast-episodes
[wikis-and-guides]: #wikis-and-guides
[other]: #further-resources

---

## Vídeos

<div class="flex-vid">
  <iframe src="https://www.youtube-nocookie.com/embed/xLYYh4aPXAM" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

[Ver todos los vídeos »][videos]

[videos]: {{ '/videos' | absolute_url }}

## Libros

Libros sobre Bitcoin que cualquiera puede leer, sin necesidad de conocimientos previos
ni educación especial. Como se mencionó anteriormente, [El Patrón Bitcoin][the-bitcoin-standard]
es una lectura obligatoria para cualquiera interesado en Bitcoin.

{% include books.html category='non-technical' above_the_fold=1 %}
{% include books.html category='non-technical' above_the_fold=2 %}

[Ver todos los libros »][books]

Categorías: [General], [Economía], [Dinero], [Banca], [Programación], [Cypherpunk], [Ficción], [Infantil]

[General]: {{ '/books/#general-bitcoin-books' | absolute_url }}
[Economía]: {{ '/books/#economics' | absolute_url }}
[Dinero]: {{ '/books/#money' | absolute_url }}
[Banca]: {{ '/books/#banking' | absolute_url }}
[Programación]: {{ '/books/#programming' | absolute_url }}
[Cypherpunk]: {{ '/books/#bitcoin-and-cypherpunk-history' | absolute_url }}
[Ficción]: {{ '/books/#fiction' | absolute_url }}
[Infantil]: {{ '/books/#bitcoin-books-for-kids' | absolute_url }}

[books]: {{ '/books' | absolute_url }}

---

## Artículos

Se han escrito muchos artículos increíbles sobre Bitcoin. Intentar
enlazarlos todos es inútil. Lo siguiente es un esfuerzo por destacar
al menos algunos de ellos. Para obtener una lista más completa de recursos,
consulta la literatura listada en el [Instituto Satoshi Nakamoto][sni] y la
selección de artículos leídos por [Bitcoin Audible][guy-episodes].

Uno de los mejores artículos para leer si eres nuevo en Bitcoin es [La Tesis Alcista de Bitcoin][bullish-case], que resume por qué hay muy buenas razones para ser
optimistas sobre el futuro de Bitcoin.

{% include articles_starred.html %}

[Ver todos los artículos »][articles]

[articles]: {{ '/articles' | absolute_url }}

---

## Podcasts

Una de las mejores formas de educarte sobre Bitcoin es escuchando a las personas
más inteligentes del sector. Afortunadamente, vivimos en la era dorada de los podcasts
y muchas grandes conversaciones son de "código abierto", por así decirlo.

Los siguientes podcasts se encuentran entre los mejores del sector:

{% include podcasts.html tier="1" %}

[Ver episodios seleccionados de podcasts »][selected-episodes] \\
[Ver todos los podcasts »][podcasts]

### Episodios de podcast seleccionados

Puedes encontrar una lista de episodios seleccionados de podcasts [aquí][selected-episodes].

[podcasts]: {{ '/podcasts' | absolute_url }}
[selected-episodes]: {{ '/podcasts#selected-podcast-episodes' | absolute_url }}

---

## Otros recursos

¡Cuantas más madrigueras de conejo, mejor! No te fíes únicamente de esta página de recursos. Existen
muchas listas y guías excelentes creadas por otros bitcoiners, como:

{% include curations_starred.html %}

[Más recursos »][further-resources]

[further-resources]: {{ '/further-resources' | absolute_url }}

---

## Acerca de estos recursos

Los recursos listados anteriormente son solo una pequeña selección que influyó especialmente
en [mi forma de pensar][dergigi]. Un sincero *gracias* a todas las personas que compartieron
sus pensamientos e ideas, pasados y presentes. He aprendido muchísimo y por ello estaré eternamente agradecido.

Si tienes sugerencias de contenido o mejoras, no dudes en abrir incidencias o PRs en [GitHub][issues] o contactar conmigo.

{% include bibliography.md %}
