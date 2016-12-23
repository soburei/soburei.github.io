---
layout: page
title: About
prec: '/search.html'
prec-title: Cerca
prox: '/docs/2_servizi.html'
prox-title: Servizi
date: 2016-12-15
update:
english:
---



Abbiamo fatto cose e visto gente nei vari [posti dell'open](https://blog.osd.tools/sod15-%C3%A8-finito-viva-i-dati-a9c2f764a75c#.i4xeezv5v). Siccome ci piace studiare e vedere l'effetto che fa abbiamo costituito *opensensorsdata (osd) srl* il [30 marzo 2015](/docs/6_statuto)).

Non lo facciamo per "[make the world a better place](https://youtu.be/IXuFrtmOYKg)" ma perché siamo curiosi e ci divertiamo impastando dati con conoscenza.

Questi siamo noi, questo il nostro [manifesto](/docs/5_manifesto.html) e i nostri [progetti](/docs/3_progetti.html).

{% for author in site.data.authors %}
<div class="profile-about">
  <div class="profile-img without-decoration">
    <a href="{{ author.img }}"><img src="{{ author.img }}" alt="foto di {{ author.full_name }}"></a>
  </div>
  <div class="author-info">
    <h3>{{ author.full_name }}</h3> <small>{{ author.description }}</small>
    <p>
      <a href="mailto:{{ author.mail }}">{{ author.mail }}</a><br>
      <a href="http://www.twitter.com/{{ author.tw }}">@{{ author.tw }}</a><br>
      <a href="http://www.github.com/{{ author.tw }}">repo github</a><br>
      <a href="http://www.telegram.com/{{ author.telegram }}">telegram</a><br>
    </p>
  </div>
</div>

{% endfor %}
