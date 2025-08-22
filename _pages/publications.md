---
layout: archive
title: "Publications"      # let the layout render the page heading once
permalink: /publications/
author_profile: true
entries_layout: list       # optional: makes items look like a list
---

{% include base_path %}
{% for post in site.publications %}
  {% include archive-single.html %}
{% endfor %}
