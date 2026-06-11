---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

This page is the full bibliography. The [CV](/cv/) keeps only selected publications for a compact professional profile, while this page keeps the complete publication record in reverse chronological order.

Research areas include **quantitative finance**, **deep learning**, **AI-driven investment**, event-driven trading, factor modeling, and financial knowledge graphs. See also [Research](/projects/) and [Google Scholar](https://scholar.google.com/citations?user=mZn8X9UAAAAJ&hl=en).

{% if author.googlescholar %}
Full citation metrics on [Google Scholar]({{ author.googlescholar }}).
{% endif %}

{% include base_path %}

## Full Bibliography

{% assign sorted_pubs = site.publications | sort: 'date' | reverse %}
{% for post in sorted_pubs %}
  {% include archive-single.html %}
{% endfor %}
