---
title: "{{ replace .Name "-" " " | title }}"
draft: false
image: /img/{{.Name}}.jpg
alt_text: "{{ replace .Name "-" " " | title }} screenshot"
summary: "Summary of the {{ replace .Name "-" " " | title }}"
tags:
    - Life
    - Health
    - Money
    - Fiction
---
This is the summary of the book "{{ replace .Name "-" " " | title }}"