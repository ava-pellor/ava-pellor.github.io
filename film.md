---
layout: default
permalink: "/film/"
---

<div class="hero film-hero">
  <h1 class="hero-title">Film</h1>
</div>

<div class="collections-container">
{% for collectiond in site.data.collections %}
{% assign collection = collectiond[1] %}

<div class="collection-container">
  <img src="/images/{{ collection.coverimg }}" alt="{{ collection.title }}">
</div>

{% endfor %}

</div>
