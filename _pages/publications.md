---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

List below updated infrequently, but you can find all my publications on [arxiv](https://arxiv.org/search/cs?searchtype=author&query=Gaidon%2C+A) or <a href="{{ site.author.googlescholar }}">my Google Scholar profile</a>.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single-paper.html %}
{% endfor %}
