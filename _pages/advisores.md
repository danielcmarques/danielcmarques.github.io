---
layout: archive
title: "Responsibly disclosed vulnerabilities"
permalink: /advisories/
author_profile: true
---

{% include base_path %}

These are vulnerabilities that I identified and reported to vendors and developers. The following information is shared with the objective to aid in the study, test, and inform. There is no intention to cause damage to third-parties.

{% for post in site.advisories reversed %}
  {% include archive-single.html %}
{% endfor %}
