---
layout: page
title: Progetti
date: 2016-12-15
prec: '/documents/2_servizi.html'
prec-title: Servizi
prox: '/documents/4_tos.html'
prox-title: ToS
update:
english:
---


<ul class="project-index">
{% for project in site.data.projects %}
  <li class="subtitle"><a href="#{{ project.id }}">{{ project.name }}</a> // </li>
{% endfor %}
</ul>


{% for project in site.data.projects %}
  <h2 id="{{ project.id }}"><a href="{{ project.site }}">{{ project.name }}</a></h2>
  <p class="project-content">
    <input type="checkbox" id="{{ project.checkbox }}" class="margin-toggle"/>
    <span class="marginnote">
      <img src="/assets/img/projects/{{ project.img }}" alt="immagine di {{ project.name }}">
      {{ project.description-en }}
    </span>
    <small>Partner: </small>
      <a href="{{ project.partner-url-1}}">{{ project.partner-1 }}</a>
    {% if project.partner-2 %}
      e <a href="{{ project.partner-url-2}}">{{ project.partner-2 }}</a>
    {% endif %}
    <br>
    <small>Data:</small> {{ project.date }}<br>
    <small>Attività:</small> {{ project.activities }}<br>
    <small>Tipo di rapporto:</small> {{ project.type }}<br>
    <br>
    <label for="{{ project.checkbox }}" class="margin-toggle">&#8853;</label><br>
    {{ project.description }}
  </p>
  <hr>
{% endfor %}
