---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% assign pubs = site.publications | sort: "date" | reverse %}

<ol>
{% for post in pubs %}
  <li>{% include archive-single-pub.html post=post %}</li>
{% endfor %}
</ol>
