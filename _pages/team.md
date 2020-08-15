---
title: "UM Geodynamics - Team"
layout: gridlay
excerpt: "UM Geodynamics: Team members"
sitemap: false
permalink: /team/
---

# Group Members

## Current
{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}<br>email: <{{ member.email }}></i>
  <ul style="overflow: hidden">

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}


## Former

<div class="row">

<div class="col-sm-8 clearfix">
<i> Chantal Newallo, Bachelor's Thesis, Spring 2020 ([Chantal's poster](/documents/chantal_newallo_poster.pdf)) </i>
</div>
</div>

## Openings

<i>Ph.D. studentships are available for Spring 2021. Get in touch if you are interested!</i>

<br>
<br>
<br>
