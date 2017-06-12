---
layout: page
permalink: /1-outline/
title: Day 1 outline
category: module
---


**Description**

---

## Outline
This tutorial session will provide a brief introduction to Data Science and data manipulation using R and the Jupyter notebooks.

The hands-on components of this module are contained in the following tutorials:

<div class='list-group'>
{% assign pages_list = site.pages %}
{% for node in pages_list %}
{% if node.title != null %}
{% if node.layout == "default" %}
{%if node.tags %}

{% for tag in node.tags %}
{% if tag == 'Day1' %}
<!-- Note you need to prepend the site.baseurl always-->
<a class='list-group-item' href="{{site.baseurl}}{{ node.url }}">{{ node.title }}</a>
{% endif %}
{% endfor %}

{% endif %}
{%endif%}
{% endif %}
{% endfor %}
</div>
