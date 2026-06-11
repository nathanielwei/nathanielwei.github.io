---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Peer-reviewed papers, preprints, and theses in **quantitative finance**, **deep learning**, and **AI-driven investment**. See also [Research projects](/projects/) and [CV](/cv/).

{% if author.googlescholar %}
Full citation metrics on [Google Scholar]({{ author.googlescholar }}).
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
