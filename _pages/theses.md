---
layout: page
permalink: /theses/
title: Current and past offered theses
description: This page lists available topics for MSc- and BSc-level theses and projects
nav: false
nav_order: 7
---

<!-- <ul>
  {% for doc in site.theses %}
    <li>
      <a href="{{ doc.url }}">{{ doc.title }}</a>
    </li>
  {% endfor %}
</ul> -->

{% assign past_projects = site.theses | where_exp: "item", "item.tags contains '2025-2026'" %}
{% assign current_projects = site.theses | where_exp: "item", "item.tags contains '2026-2027'" %}

{% if current_projects.size > 0 %}
  <h3>Current projects (Academic year 2026 - 2027)</h3>
  <ul>
    {% for doc in current_projects %}
      <li>
        <a href="{{ doc.url }}">{{ doc.title }}</a>
      </li>
    {% endfor %}
  </ul>
{% endif %}

{% if past_projects.size > 0 %}
  <h3>Past projects (Academic years 2024 - 2026)</h3>
  <ul>
    {% for doc in past_projects %}
      <li>
        <a href="{{ doc.url }}">{{ doc.title }}</a>
      </li>
    {% endfor %}
  </ul>
{% endif %}