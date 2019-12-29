---
layout: archive
permalink: /notes/
---

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}

{% include paginator.html %}
