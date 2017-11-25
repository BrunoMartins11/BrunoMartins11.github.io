---
layout: archive
title: "Interests"
permalink: /about/
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% if author.googlescholar %}
  Because University is not all about going to class and spending all my time studying I like to entertain myself doing other things, such as playing Basketball, going to the gym, ocasionaly game with my friends and learn more about computer science.
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
