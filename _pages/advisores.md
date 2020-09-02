---
layout: archive
title: "Responsibly disclosed vulnerabilities"
permalink: /advisories/
author_profile: true
---

{% include base_path %}

{% for post in site.advisories reversed %}
  {% include archive-single.html %}
{% endfor %}
