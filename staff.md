---
layout: page
title: Me
description: A listing of all the course staff members.
---

# Staff

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% assign num_instructors = instructors | size %}

{% if num_instructors == 1 %}

## Instructor

{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% elsif num_instructors != 0 %}

## Instructors

{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% endif %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}

## Teaching Assistants

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}
