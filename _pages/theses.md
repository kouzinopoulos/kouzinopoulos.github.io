---
layout: page
permalink: /theses/
title: Offered theses - academic year 2025 - 2026
description: This page lists available topics for MSc- and BSc-level theses and projects
nav: false
nav_order: 7
---

<h1>{{ page.title }}</h1>

<ul>
  {% for doc in site.theses %}
    <li>
      <a href="{{ doc.url }}">{{ doc.title }}</a>
    </li>
  {% endfor %}
</ul>
