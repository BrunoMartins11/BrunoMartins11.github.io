permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from:
  - /computer/
  - /about.html

*Imperative Programming
*Functional Programming
*Linux
*Debugging



{% include base_path %}


{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
