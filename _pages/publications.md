<h2>Papers</h2>
<ol>
{% for post in site.publications %}
  <li>{% include archive-single-pub.html post=post %}</li>
{% endfor %}
</ol>

