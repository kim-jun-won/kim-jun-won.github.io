---
title : "Github Blog tutorial"
layout : archive
permalink : categories/blog
author_profile : true
sidebar_main : true
---

{% assign posts = site.categories.Blog %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}