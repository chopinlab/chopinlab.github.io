---
title: "Post about Private"
layout: archive
permalink: /categories/private
author_profile: true
sidebar_main: true
---

{% assign posts = site.categories.private | sort:"date" %}

{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}
