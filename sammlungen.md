---
title: Sammlungen/Blog
subtitle: <small>Tolle Folgen anderer Podcasts, Gastauftritte und noch mehr.</small>
layout: page
author: Jana
explicit: 'no'
navigation: 2
---



{% for sammlung in site.sammlungen reversed %}
  <h2><a href="{{ sammlung.url }}">{{ sammlung.title }}</a> <small>{{ sammlung.subtitle}}</small></h2>



  {{ sammlung.excerpt }}
{% endfor %}
