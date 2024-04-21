---
layout: resources
title: Videos de Bitcoin
image: /assets/images/bitcoin-resources-twitter-cover.png
description: Selección de videos de Bitcoin.
---

Visita [BitcoinTV.com](https://bitcointv.com/), una plataforma de video enfocada en Bitcoin.

---

<center>
  <p><small><a href="#toc">↓ Tabla de contenidos ↓</a></small></p>
</center>

---

### Videos seleccionados

Los videos listados a continuación son recomendados, tanto si eres un novato
o ya tengas más experiencia. Estos videos individuales cubren un amplio 
abanico de temas.

<div class="flex-vid">
  <iframe src="https://www.youtube-nocookie.com/embed/xLYYh4aPXAM" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<div class="flex-vid">
  <iframe src="https://www.youtube-nocookie.com/embed/IAFKJVLNVQA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<div class="flex-vid">
  <iframe src="https://www.youtube-nocookie.com/embed/hBVXNpkdPBU" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<div class="flex-vid">
  <iframe src="https://www.youtube-nocookie.com/embed/NoobUKNttmw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<div class="flex-vid">
  <iframe src="https://www.youtube-nocookie.com/embed/lkZLm_0ynXQ" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<div class="flex-vid">
  <iframe src="https://www.youtube-nocookie.com/embed/uTgDQ56Su38" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<div class="flex-vid">
  <iframe src="https://www.youtube-nocookie.com/embed/nvtGQ-7O1Tw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<div class="flex-vid">
  <iframe src="https://www.youtube-nocookie.com/embed/9vM0oIEhMag" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<div class="flex-vid">
  <iframe src="https://www.youtube-nocookie.com/embed/iVym9wtopqs" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<div class="flex-vid">
  <iframe src="https://www.youtube-nocookie.com/embed/7vl_ziH6OJo" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

### Canales de YouTube seleccionados

- [Swan Bitcoin](https://www.youtube.com/channel/UCl4takhOQtiyprismCPsa2Q)
- [Ioni Appelberg](https://www.youtube.com/user/waem)
- [Till Musshoff](https://www.youtube.com/c/TillMusshoff)
- [Saifedean Ammous](https://www.youtube.com/c/SaifedeanVideos)
- [Microstrategy](https://www.youtube.com/c/microstrategy)
- [TFTC](https://www.youtube.com/c/TFTC21)
- [Citadel Dispatch](https://www.youtube.com/channel/UCoA72saVAuQ8hYCnBO0Lymw)
- [402 Payment Required](https://www.youtube.com/c/402PaymentRequired)
- [BTC Sessions](https://www.youtube.com/c/BTCSessions)
- [Robert Breedlove](https://www.youtube.com/c/RobertBreedlove22)
- [Natalie Brunell](https://www.youtube.com/c/nataliebrunellpodcasts)
- [Kiara Bickers](https://www.youtube.com/channel/UCEjLeFAlTxymys0Ov3zbmbg)
- [Giacomo Zucco](https://www.youtube.com/channel/UCYAZrTL0h0EaGahEPn6qxAg)
- [Pleb Music](https://www.youtube.com/channel/UC32zG7alhxoCmHxId9uBl-g)
- [Ministry of Nodes](https://www.youtube.com/c/MinistryofNodes)
- [Simply Bitcoin](https://www.youtube.com/c/SimplyBitcoin)
- [Hello Bitcoin](https://www.youtube.com/channel/UCL_zH0Q088KNHFDkd5FLadw)
- [Pleb Underground](https://www.youtube.com/channel/UCVfMv5xEfrafk1rSthJ0t9g)
- [Bitcoin Kindergarten](https://www.youtube.com/c/BitcoinKindergarten)
- [Bitcoin Optech](https://www.youtube.com/channel/UCUyjLD_zRr4F8nKaCtZHXUg)

### Playlist seleccionadas

- [Bitcoin Explained](https://www.youtube.com/playlist?list=PL_xlkwLDH1F-J-THOZfn9SzSgBs2uGYIn) de The Investor's Podcast Network
- [The Saylor Series](https://www.youtube.com/playlist?list=PL2jAZ0x9H0bQFY6wIbQfnrnIlqMcSHd6X)
- [The Vervaeke Series](https://www.youtube.com/playlist?list=PL2jAZ0x9H0bTK1nFYSZhRGq18SGkW8kgG)
- [The Twilight of Gold](https://www.youtube.com/playlist?list=PL2jAZ0x9H0bR3eCyc-lBmv8u6s88csYEW)

### Podcasts con canales de YouTube

{% assign yt_pods = '' | split: '' %}
{% for pod in site.podcasts %}
{% if pod.youtube %}{% assign yt_pods = yt_pods | push: pod %}{% endif %}
{% endfor %}
{% for pod in yt_pods %}
- [{{ pod.name }}]({{ pod.youtube }})
{% endfor %}

Entra en [podcasts](/podcasts) para ver la lista completa con todos los podcasts.

### Bonus: On the Art of Hodling

{% assign absoluteVideoUrl = '/assets/videos/american-hodl.mp4' | absolute_url %}
{% include video.html file=absoluteVideoUrl %}


---

[« Volver al índice][index]

[index]: {{ '#books' | absolute_url }}

{% include bibliography.md %}
