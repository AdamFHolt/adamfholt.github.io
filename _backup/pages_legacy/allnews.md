---
title: "News"
layout: textlay
excerpt: "Geodynamics at the University of Miami."
sitemap: false
permalink: /allnews.html
---

<h3 style="font-weight: bold">News</h3> 

<hr>
{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
<br>
<br>