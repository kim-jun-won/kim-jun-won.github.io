---
title : "tag"
layout : tags
permalink : /tags/
author_profile : true
sidebar_main : true
--- 

{% assign posts = site.categories %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}