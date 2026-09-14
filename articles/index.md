---
layout: resources
title: Artículos de Bitcoin
image: /assets/images/bitcoin-resources-twitter-cover.png
description: Selección de artículos de Bitcoin.
---

Se han escrito muchos artículos increíbles sobre Bitcoin. Soy consciente de que intentar
enlazarlos todos es inútil, pero quiero hacer un esfuerzo y al menos
destacar algunos de ellos. Recomiendo encarecidamente la [literatura listada][sni] en el
Instituto Nakamoto, la selección de [artículos leídos][guy-episodes] por
Guy Swann y los [escritos recopilados][brh-writings] por Adam Taché.

Uno de los mejores artículos para leer si eres nuevo en Bitcoin es [La Tesis Alcista de Bitcoin][bullish-case], que resume por qué hay muy buenas razones para ser
optimistas sobre el futuro de Bitcoin.

- [La Tesis Alcista de Bitcoin][bullish-case] de Vijay Boyapati

---

<center>
  <p><small><a href="#toc">↓ Tabla de contenidos ↓</a></small></p>
</center>

---

## Serie de artículos

<ul class="articles">
{% for s in site.series %}
  <li><a href="{{ s.url }}">{{ s.title }}</a>
  por {{ s.author }}</li>
{% endfor %}
</ul>

---

## La dificultad de entender Bitcoin

Bitcoin no es exactamente fácil de entender. Algunas de las razones de este
fenómeno se exploran en los siguientes artículos:

{% include articles.html category='The Difficulty of Understanding Bitcoin' %}

Exploro la naturaleza multidisciplinaria de Bitcoin en [21 Lecciones].

[21 Lecciones]: http://21lessons.com

## La singularidad de Bitcoin

¿Por qué Bitcoin y no otra cosa? Porque Bitcoin importa, Bitcoin es único,
Bitcoin es justo y Bitcoin es mucho mejor de lo que piensas.

{% include articles.html category="Bitcoin's Uniqueness" %}

## Dinero

Si aún no estás listo para leer [libros sobre dinero][moneybooks], estos artículos son un
excelente punto de entrada para comenzar a aprender sobre el propósito y la historia del dinero.

{% include articles.html category='Money' %}

Escribí sobre el dinero y la historia y caída del dinero en la [Lección
11][lesson-11] y la [Lección 12][lesson-12].

[lesson-11]: https://21lessons.com/11
[lesson-12]: https://21lessons.com/12

## Prueba de trabajo

En mi opinión, la prueba de trabajo es una de las partes más incomprendidas del
rompecabezas de Bitcoin. Resuelve múltiples problemas, convirtiéndose en una de las partes más
integrales del sistema. Los siguientes artículos exploran la prueba de trabajo con más
detalle:

{% include articles.html category='Proof-of-work' %}

Escribí sobre cómo cambié mi perspectiva sobre la prueba de trabajo en [Consumo de energía de Bitcoin:
Un cambio de perspectiva][energy-consumption] y en la [Lección 17][lesson-17].

[energy-consumption]: https://dergigi.com/2018/06/10/bitcoin-s-energy-consumption/
[lesson-17]: https://21lessons.com/17
[moneybooks]: {{ '/books/#money' | absolute_url }}

## La identidad de Bitcoin

¿Qué es Bitcoin? Esta pregunta es sorprendentemente difícil de responder. Es una
red (Bitcoin), dinero (bitcoin), software (varias implementaciones), una idea
(el libro blanco), un registro inmutable de propiedad (el contable de Bitcoin, también conocido como la
"cadena de bloques"), un movimiento, una revolución monetaria y más.

{% include articles.html category="Bitcoin's Identity" %}

Exploro la identidad de Bitcoin en la [Lección 4][lesson-4] y en [La gravedad de
Bitcoin][gravity].

[lesson-4]: https://21lessons.com/4
[gravity]: https://dergigi.com/2019/05/01/bitcoins-gravity/

## Una revolución social

Bitcoin no es solo un fenómeno tecnológico, financiero y monetario, también es
una revolución global. Bitcoin cautiva los corazones y las mentes de personas en todo el
mundo, cambiando la sociedad en el proceso. Hoy en día, existen decenas de miles de
"bitcoiners en el armario" en todo el mundo y Bitcoin ha desarrollado un ferviente grupo
de seguidores.

{% include articles.html category='A Social Revolution' %}

Exploro algunos de los impactos sociales en la [Lección 1][lesson-1] y escribí sobre
algunos de estos impactos en [El surgimiento del individuo
soberano][rise-of-the-sovereign-individual].

[lesson-1]: https://21lessons.com/1
[rise-of-the-sovereign-individual]: https://medium.com/bull-bitcoin/the-rise-of-the-sovereign-individual-2201eee82f00

## ¿Quién controla Bitcoin?

Una de las primeras respuestas de las personas que aprenden sobre Bitcoin es "Sí, sí, lo
entiendo... ¿pero quién lo controla?" La pregunta del control no es fácil de
responder, porque hay que entender todo el sistema a un nivel bastante profundo para
responderla. Los siguientes artículos podrían ayudar.

{% include articles.html category="Who Controls Bitcoin?" %}

Exploro la cuestión del control (y la censurabilidad) en la [Lección 6][lesson-6]
y en [El polvo mágico de la criptografía][magic-dust].

[magic-dust]: https://dergigi.com/2018/08/17/the-magic-dust-of-cryptography/
[lesson-6]: https://21lessons.com/6

## Bitcoin como un organismo vivo

Ralph Merkle dijo la famosa frase de que Bitcoin es ["el primer ejemplo de una nueva forma de
vida."][dao-merkle]. Otros desarrollaron más esta idea, que es, en mi
opinión, una de las analogías más útiles para entender Bitcoin.

{% include articles.html category="Bitcoin as a Living Organism" %}

Exploro la idea de Bitcoin como un organismo vivo en [Prueba de
vida][proof-of-life] y [Los hábitats de Bitcoin][bitcoins-habitats].

[proof-of-life]: https://dergigi.com/2019/08/07/proof-of-life/
[bitcoins-habitats]: https://dergigi.com/2020/03/01/bitcoin-s-habitats/

## Hiperbitcoinización

El concepto de Hiperbitcoinización describe el punto de inflexión en el que
Bitcoin se convierte en el sistema de valor predeterminado del mundo. Al igual que un evento de hiperinflación,
se postula que este proceso sucederá gradualmente, y luego repentinamente.

{% include articles.html category="Hyperbitcoinization" %}

## Cypherpunks

Bitcoin es tecnología cypherpunk. Hecha por un cypherpunk, basada en ideas cypherpunk.
Considero esencial la exposición a las ideas y los ideales de la cultura cypherpunk.

{% include articles.html category="Cypherpunks" %}

## Privacidad

Sin dinero en efectivo digital, una sociedad sin efectivo es una sociedad de vigilancia. Aunque
la privacidad en Bitcoin no se da por sentada, existen varias formas de realizar transacciones de forma privada.
Los siguientes recursos analizan estas posibilidades, por qué es esencial el derecho a realizar transacciones
de forma privada y por qué debe ser protegido.

{% include articles.html category="Privacy" %}

## Varios

Los siguientes son lo que considero artículos excelentes que no encajaban en una
de mis categorías elegidas arbitrariamente anteriormente.

{% include articles.html category="Misc" %}

[Lista de todos los artículos »][article-list]

[article-list]: {{ '/articles/all' | absolute_url }}

---

[« volver al índice][index]

[index]: {{ '#articles' | absolute_url }}

{% include bibliography.md %}
