---
layout: page
permalink: /theses/
title: Current and past offered theses
description: This page lists available topics for MSc- and BSc-level theses and projects
nav: false
nav_order: 7
---

{% assign current_projects = site.theses | where_exp: "item", "item.tags contains '2026-2027'" %}

{% if current_projects.size > 0 %}
  <h3>Current projects (Academic year 2026 - 2027)</h3>

  {% assign space_projects = current_projects | where_exp: "item", "item.tags contains 'space'" %}
  {% if space_projects.size > 0 %}
    <h4>Space domain</h4>
    <ul>
      {% for doc in space_projects %}
        <li>
          <a href="{{ doc.url }}">{{ doc.title }}</a>
        </li>
      {% endfor %}
    </ul>
  {% endif %}

  {% assign gw_projects = current_projects | where_exp: "item", "item.tags contains 'GW'" %}
  {% if gw_projects.size > 0 %}
    <h4>Gravitational Waves domain</h4>
    <ul>
      {% for doc in gw_projects %}
        <li>
          <a href="{{ doc.url }}">{{ doc.title }}</a>
        </li>
      {% endfor %}
    </ul>
  {% endif %}

  {% assign uncategorized = current_projects | where_exp: "item", "item.tags contains 'space' == false and item.tags contains 'GW' == false" %}
  {% if uncategorized.size > 0 %}
    <h4>Other domains</h4>
    <ul>
      {% for doc in uncategorized %}
        <li>
          <a href="{{ doc.url }}">{{ doc.title }}</a>
        </li>
      {% endfor %}
    </ul>
  {% endif %}

{% assign past_projects = site.theses | where_exp: "item", "item.tags contains '2025-2026'" %}

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