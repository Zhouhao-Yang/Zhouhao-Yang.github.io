---
layout: single
title: "Publications"
permalink: /publications/
author_profile: true
---


You can also find my articles on my [Google Scholar profile]({{ site.author.googlescholar }}).


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
