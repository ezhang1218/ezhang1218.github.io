---
layout: archive
title: "Papers"
permalink: /publications/
---

{% for post in site.publications %}
  <li>{% include archive-single-pub.html post=post %}</li>
{% endfor %}
