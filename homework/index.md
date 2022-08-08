---
layout: page
title: Homework
nav_order: 2
description: Course homework assignments
has_children: true
has_toc: false
---

# Homework 

{% assign homeworks = site.pages | where: "tag", "homework" | reverse %}
{% for homework in homeworks %}
 - [{{ homework.title }}]({{ homework.url }}). Due Date: {{ homework.date | date: "%B %-d" }}
{% endfor %}