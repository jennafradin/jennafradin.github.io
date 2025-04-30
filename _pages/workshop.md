---
layout: archive
title: "Workshops"
permalink: /workshops/
author_profile: true
---

{% include base_path %}

{% for post in site.workshop reversed %}
  {% include archive-single.html %}
{% endfor %}
