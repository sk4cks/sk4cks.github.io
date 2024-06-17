---
title: "Vanilla JS"
layout: category
permalink: /js/vanilla/
author_profile: true
sidebar_main: true
sidebar:
    nav: "sidebar-category"
---

{% assign posts = site.categories.vanillaJs %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}