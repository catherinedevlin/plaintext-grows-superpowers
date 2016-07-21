---
title: IEEE-Dayton
layout: default
---

Welcome to IEEE-Dayton!
=======================

This page is located at {{ page.url }}

We like

- code
- pizza
- code about pizza

Here are some great languages.

{% for lang in site.data.languages %}
- {{ lang.name }} (**.{{ lang.extension }}**)
{% endfor %}

[Back to our homepage.](../)
