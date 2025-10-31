<h2>Publications</h2>
<ol>
{% for post in site.publications %}
  <li>{% include archive-single-pub.html post=post %}</li>
{% endfor %}
</ol>

<h2>Preprints</h2>
<ol>
{% for post in site.preprints %}
  <li>{% include archive-single-pub.html post=post %}</li>
{% endfor %}
</ol>
