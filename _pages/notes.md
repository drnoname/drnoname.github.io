---
layout: home
permalink: /notes/
category: notes
title: &title "Notes"
alt_title: *title
introduction: *excerpt
pagination:
  enabled: true
  category: notes
---

{% for post in paginator.posts.notes %}
  {% include archive-single.html %}
{% endfor %}
