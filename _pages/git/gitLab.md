---
title: "GitLab"
layout: category
permalink: /git/gitLab/
author_profile: true
sidebar_main: true
sidebar:
    nav: "sidebar-category"
---

{% assign posts = site.categories.gitLab %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}