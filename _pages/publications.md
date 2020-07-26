---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

Partial list. You can also find my articles on <a href="{{ site.author.googlescholar }}">my Google Scholar profile</a>.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single-paper.html %}
{% endfor %}
