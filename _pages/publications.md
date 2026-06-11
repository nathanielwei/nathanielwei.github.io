---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<section class="pub-hero">
  <p class="eyebrow">Full Bibliography</p>
  <h1>Publications</h1>
  <p>
    Complete publication record in quantitative finance, deep learning, AI-driven investment,
    event-driven trading, factor modeling, and financial knowledge graphs.
  </p>
  <div class="hero-actions">
    <a class="button-primary" href="https://scholar.google.com/citations?user=mZn8X9UAAAAJ&hl=en">Google Scholar</a>
    <a class="button-secondary" href="/cv/">Selected Publications in CV</a>
    <a class="button-secondary" href="/projects/">Research Projects</a>
  </div>
</section>

The [CV](/cv/) page keeps a compact selected list. This page is the full bibliography, organized by year.

{% include base_path %}

{% assign sorted_pubs = site.publications | sort: 'date' | reverse %}
{% assign current_year = "" %}
<section class="publication-timeline">
{% for post in sorted_pubs %}
  {% assign post_year = post.date | date: "%Y" %}
  {% if post_year != current_year %}
    {% unless forloop.first %}
      </div>
    {% endunless %}
    <h2 class="pub-year">{{ post_year }}</h2>
    <div class="pub-year-group">
    {% assign current_year = post_year %}
  {% endif %}

  <article class="publication-card">
    <div class="publication-card-main">
      <h3><a href="{{ base_path }}{{ post.url }}">{{ post.title }}</a></h3>
      <p class="publication-meta">{{ post.venue }}</p>
      {% if post.citation %}
        <details class="publication-citation">
          <summary>Citation</summary>
          <p>{{ post.citation }}</p>
        </details>
      {% endif %}
    </div>
    <div class="publication-actions">
      <a href="{{ base_path }}{{ post.url }}">Details</a>
      {% if post.paperurl %}
        <a href="{{ post.paperurl }}">Paper</a>
      {% endif %}
    </div>
  </article>
{% endfor %}
  </div>
</section>
