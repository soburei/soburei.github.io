---
layout: document
title: Servizi
display-order: 3
---

This is the base Jekyll theme. You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](http://jekyllrb.com/)

You can find the source code for the Jekyll new theme at:
 /
[minima](https://github.com/jekyll/minima)

You can find the source code for Jekyll at
 /
[jekyll](https://github.com/jekyll/jekyll)

<div class="page-price-cards">
  <div class="card-container-page">
    {% for price in site.data.prices %}
    <div class="card">
      <div class="card-title">
        <span class="card-period">{{ price.period }}</span>
        <span class="card-deliver">{{ price.deliver }}</span>
      </div>
      <div class="card-prezzo">
        <span class="card-period">{{ price.cost }}</span>
        <img src="/assets/img/icons/{{ price.icon }}" alt="price icon" />
      </div>
    </div>
    {% endfor %}
  </div>
</div>


<h1 id="probono">Probono</h1>
<h4>Perchè offriamo i nostri servizi pro bono e perchè dovresti contattarci</h4>

Noi di OSD abbiamo fatto parte del movimento opendata fin dai primi anni. Abbiamo visto e contribuito alla sua crescita. Gli effetti sono ora visibili in diversi campi; dalla trasparenza al civic engagement fino alla conservazione dei beni pubblici. Ma sappiamo bene che le radici del movimento affondano nell'attivismo, nella passione civica e in tanti piccoli esperimenti locali. Lo sappiamo, eravamo lì. Ecco perchè offriamo i nostri servizi a chi non può altrimenti accederci ma che dimostra chiaramente un potenziale impatto nella scena del riuso e della produzione dei dati aperti.

Se pensi di essere un buon candidato faccelo sapere. Scarica il form dal link in basso. Ti chiediamo di compilarlo perchè senza avere un quadro chiaro del tuo progetto, della tua missione e di come vuoi portarla a termine non saremmo in grado di valutare la tua proposta, nè di fartene una concreta e adeguata alle tue esigenze.
