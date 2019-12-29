---
layout: archive
permalink: /notes/
---

{{ content }}

{% for post in paginator.posts.notes %}
  {% include archive-single.html %}
{% endfor %}

{% include paginator.html %}
