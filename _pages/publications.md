---
layout: single
title: "Publications"
permalink: /publications/
author_profile: true
---


You can also find my articles on my [Google Scholar profile]({{ site.author.googlescholar }}).


{% include base_path %}

{% assign in_preparation = site.publications | where: "publication_status", "in_preparation" | reverse %}
{% assign submitted = site.publications | where: "publication_status", "submitted" | reverse %}
{% assign to_appear = site.publications | where: "publication_status", "to_appear" | reverse %}
{% assign published = site.publications | where: "publication_status", "published" | reverse %}

<h2 class="archive__subtitle">In Preparation</h2>
{% for post in in_preparation %}
  {% include archive-single.html %}
{% endfor %}

<h2 class="archive__subtitle">Submitted</h2>
{% for post in submitted %}
  {% include archive-single.html %}
{% endfor %}

<h2 class="archive__subtitle">To Appear</h2>
{% for post in to_appear %}
  {% include archive-single.html %}
{% endfor %}

<h2 class="archive__subtitle">Published</h2>
{% for post in published %}
  {% include archive-single.html %}
{% endfor %}
