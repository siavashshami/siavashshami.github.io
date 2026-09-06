---
layout: archive
title: "Resources"
show_title: false
permalink: /resources/
author_profile: true
---

## 💻 Codes & Scripts

{% if site.code.size > 0 %}
<ul>
  {% for item in site.code %}
    <li>
      <a href="{{ item.url }}">{{ item.title }}</a>
      {% if item.excerpt %} - {{ item.excerpt }}{% endif %}
    </li>
  {% endfor %}
</ul>
{% else %}
<p>No code or scripts have been added yet.</p>
{% endif %}

---

## 🛠️ Software

{% if site.software.size > 0 %}
<ul>
  {% for item in site.software %}
    <li>
      <a href="{{ item.url }}">{{ item.title }}</a>
      {% if item.excerpt %} - {{ item.excerpt }}{% endif %}
    </li>
  {% endfor %}
</ul>
{% else %}
<p>No software has been added yet.</p>
{% endif %}

---

## 📊 Datasets

{% if site.data_pages.size > 0 %}
<ul>
  {% for item in site.data_pages %}
    <li>
      <a href="{{ item.url }}">{{ item.title }}</a>
      {% if item.excerpt %} - {{ item.excerpt }}{% endif %}
    </li>
  {% endfor %}
</ul>
{% else %}
<p>No datasets have been added yet.</p>
{% endif %}

---

## 📚 Tutorials

{% if site.tutorials.size > 0 %}
<ul>
  {% for item in site.tutorials %}
    <li>
      <a href="{{ item.url }}">{{ item.title }}</a>
      {% if item.excerpt %} - {{ item.excerpt }}{% endif %}
    </li>
  {% endfor %}
</ul>
{% else %}
<p>No tutorials have been added yet.</p>
{% endif %}
