---
layout: archive
title: "Professional Activities"
permalink: /professional/
author_profile: true
---

{% include base_path %}

{% for post in site.professional reversed %}
{% include archive-single.html %}
{% endfor %}
