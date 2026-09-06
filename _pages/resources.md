---
title: "Resources"
permalink: /resources/
layout: single
---

Welcome to my **Resources** page. Here you will find a curated collection of tools, datasets, and materials I have developed or contributed to during my research in **Geodesy**, **InSAR**, and **Remote Sensing**. Feel free to explore, download, and use them in your own work.

---

## 📑 Quick Access
- [💻 Codes & Scripts](#codes)
- [🛠️ Software](#software)
- [📊 Datasets](#datasets)
- [📚 Tutorials](#tutorials)

---

## 💻 Codes & Scripts {#codes}
{% if site.code.size > 0 %}
  {% for item in site.code %}
  - 🐍 [**{{ item.title }}**]({{ item.url }})  
    {{ item.excerpt }}
  {% endfor %}
{% else %}
<p style="color: #888;">No codes available yet. Check back later!</p>
{% endif %}

---

## 🛠️ Software {#software}
{% if site.software.size > 0 %}
  {% for item in site.software %}
  - ⚙️ [**{{ item.title }}**]({{ item.url }})  
    {{ item.excerpt }}
  {% endfor %}
{% else %}
<p style="color: #888;">No software available yet. Check back later!</p>
{% endif %}

---

## 📊 Datasets {#datasets}
{% if site.data_pages.size > 0 %}
  {% for item in site.data_pages %}
  - 📁 [**{{ item.title }}**]({{ item.url }})  
    {{ item.excerpt }}
  {% endfor %}
{% else %}
<p style="color: #888;">No datasets available yet. Check back later!</p>
{% endif %}

---

## 📚 Tutorials {#tutorials}
{% if site.tutorials.size > 0 %}
  {% for item in site.tutorials %}
  - 📖 [**{{ item.title }}**]({{ item.url }})  
    {{ item.excerpt }}
  {% endfor %}
{% else %}
<p style="color: #888;">No tutorials available yet. Check back later!</p>
{% endif %}

---

*Last updated: {{ site.time | date: '%B %d, %Y' }}*
