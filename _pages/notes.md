---
layout: archive
permalink: /notes/
---

{% for post in paginator.posts.notes %}
  {% include archive-single.html %}
{% endfor %}

{% include paginator.html %}
