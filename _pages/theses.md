---
layout: page
permalink: /theses/
title: theses
description: Theses
nav: false
nav_order: 7
---


<h2>Offered theses 2025 - 2026</h2>

This page lists available topics for MSc- and BSc-level theses and projects


<h1>{{ page.title }}</h1>

<ul>
  {% for doc in site.theses %}
    <li>
      <a href="{{ doc.url }}">{{ doc.title }}</a>
    </li>
  {% endfor %}
</ul>





