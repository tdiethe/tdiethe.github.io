---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<!-- {% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->

Books
------------------------

{% bibliography --file books %}

Book Chapters
--------------------

{% bibliography --file bookchapters %}

Theses
-----

{% bibliography --file theses %}


Journals
-----

{% bibliography --file journals %}

Conferences
-----

{% bibliography --file conferences %}


Tech Reports
-----

{% bibliography --file techreports %}

