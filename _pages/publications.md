---
layout: archive
title: "Featured Publications"
permalink: /publications/
author_profile: true
---

Please see my CV for a full list.
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
