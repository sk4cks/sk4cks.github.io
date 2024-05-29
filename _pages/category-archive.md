---
title: "Category"
layout: archive
permalink: /categories/
author_profile: true
sidebar_main: true
sidebar:
    nav: "sidebar-category"
---

<nav>
  <ul>
    {% for item in site.data.navigation.sidebar-category %}
      <li><a href="{{ item.url }}">{{ item.title }}</a></li>
    {% endfor %}
  </ul>
</nav>

<main>
    <h1>{{ page.title }}</h1>
    <ul>
    {% for category in site.categories %}
        {% assign category_name = category | first %}
        {% assign posts_in_category = category | last %}
        <li>
        <a href="{{ site.baseurl }}/{{ category_name | slugify }}/">
            {{ category_name | capitalize }} ({{ posts_in_category | size }})
        </a>
        </li>
    {% endfor %}
    </ul>
</main>