---
title: "UM Geodynamics - Team"
layout: gridlay
excerpt: "UM Geodynamics - Team"
sitemap: false
permalink: /team/
---

<h3 style="font-weight: bold">Group members</h3> 
<hr>
<h3 style="font-weight: bold">Current:</h3>
{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="27%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}<br>email: <{{ member.email }}></i>
  <ul style="overflow: hidden">

  {% if member.number_addit == 1 %}
  <li> {{ member.addit1 }} </li>
  {% endif %}

  {% if member.number_addit == 2 %}
  <li> {{ member.addit1 }} </li>
  <li> {{ member.addit2 }} </li>
  {% endif %}

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


<h3 style="font-weight: bold">Former:</h3>

<div class="row">

<div class="col-sm-8 clearfix">
<i> Sam Goldberg, NSF Postdoc Fellow, Now faculty here in Miami ([Sam's webpage](https://www.samgoldberg.org/)) </i>
<br><i> Yidan Wang, Now in Prof. G. Lin's seismology group, Summer 2022 ([Yidan's poster](/documents/posters/yidan_ALW_poster.pdf)) </i>
<br><i> Jazmin Garza, Bachelor's Thesis, Spring 2022 ([Jazmin's poster](/documents/posters/jazmin_garza_poster.pdf)) </i>
<br><i> Chantal Newallo, Bachelor's Thesis, Spring 2020 ([Chantal's poster](/documents/posters/chantal_newallo_poster.pdf)) </i>

</div>
</div>

<h3 style="font-weight: bold">Openings:</h3>

<i>Ph.D. studentships are available for Fall 2023. See [here](https://graduate.earth.miami.edu/_assets/pdf/phd-assistanships/adam-holt1-fall-2023.pdf) and [here](https://graduate.earth.miami.edu/_assets/pdf/phd-assistanships/adam-holtt2-fall-2023.pdf) for more details about the projects and get in touch if interested!</i>

<!-- <h3 style="font-weight: bold">Group outings:</h3>
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/teampic/SharkValley_Feb2022.png" width="100%">
</figure>
 -->
<br>
<br>
