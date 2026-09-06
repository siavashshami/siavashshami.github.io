---
title: "Resources"
permalink: /resources/
layout: default

---

# Resources

Welcome to my resources page. Here you can find my codes, software, datasets, and tutorials.

## Codes & Scripts

{% for item in site.code %}
- [{{ item.title }}]({{ item.url }})
{% else %}
No codes available yet.
{% endfor %}

## Software

{% for item in site.software %}
- [{{ item.title }}]({{ item.url }})
{% else %}
No software available yet.
{% endfor %}

## Datasets

{% for item in site.data_pages %}
- [{{ item.title }}]({{ item.url }})
{% else %}
No datasets available yet.
{% endfor %}

## Tutorials

{% for item in site.tutorials %}
- [{{ item.title }}]({{ item.url }})
{% else %}
No tutorials available yet.
{% endfor %}
