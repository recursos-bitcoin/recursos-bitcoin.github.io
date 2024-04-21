---
layout: resources
title: Etiquetas
image: /assets/images/bitcoin-resources-twitter-cover.png
description: Podcasts de Bitcoin categorizadas por etiquetas
---


Bitcoin parece generar una lista interminable de podcast. Categorizarlos por
etiquetas ayuda a dividir la larga (y creciente) lista.

---

<center>
  <p><small><a href="#toc">↓ Tabla de contenidos ↓</a></small></p>
</center>

{% include tags.html %}
{% for tag in tags %}
---
### {{ tag | capitalize }}
{% include tagged-resources.html tag=tag %}
{% endfor %}
