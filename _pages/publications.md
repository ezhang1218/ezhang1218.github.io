---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<ol>
{% for post in site.publications %}
  <li>{% include archive-single-pub.html post=post %}</li>
{% endfor %}
</ol>
