---
title: "Command"
layout: category
permalink: /linux/command/
author_profile: true
sidebar_main: true
sidebar:
    nav: "sidebar-category"
---

{% assign posts = site.categories.command %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}