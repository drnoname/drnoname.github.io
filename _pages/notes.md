---
layout: archive
permalink: /notes/
---

Hahaha

{{paginator.posts}}

{% for post in paginator.posts %}
  {% include archive-single.html %}
{% endfor %}

{% include paginator.html %}
