---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Accepted Publications
======

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Submitted Publications
======
{% for post in site.submitted reversed %}
  {% include archive-single.html %}
{% endfor %}