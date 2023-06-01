---
layout: archive
title: "Workshops and Events"
permalink: /events/
author_profile: true
---

{% for post in site.events reversed %}
  {% include archive-single-event.html %}
{% endfor %}
