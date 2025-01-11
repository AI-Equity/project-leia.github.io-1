---
layout: single
title: Resources
permalink: /resources/
author_profile: true
toc: true
toc_label: "Resources TOC"
toc_icon: "fa-solid fa-robot"  # corresponding Font Awesome icon name (without fa prefix)
---
# What is this page for?

# Blog Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
# List of Interesting Papers

# List of Interesting Code Examples