---
layout: archive
title: "Recognition"
permalink: /recognition/
author_profile: true
---

{% include base_path %}

{% for post in site.recognition reversed %}
  {% include archive-single.html %}
{% endfor %}
