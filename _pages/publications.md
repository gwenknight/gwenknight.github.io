---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% include base_path %}

Publications
======

For an up to date list of my publications, please refer to my 
[Google Scholar profile](https://scholar.google.co.uk/citations?hl=en&user=pBZCLwEAAAAJ&view_op=list_works&sortby=pubdate).


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
