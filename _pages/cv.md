---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<section class="profile-hero cv-hero">
  <p class="eyebrow">Curriculum Vitae</p>
  <h1>Zikai (Nathaniel) Wei</h1>
  <p class="hero-copy">
    Quantitative AI researcher with a PhD from MMLab, CUHK. Industry experience at a top-tier hedge fund
    in Hong Kong and a top-tier asset management firm in mainland China. Research focus: end-to-end deep
    learning for active investing, adaptive factor models, and event-driven trading.
  </p>
  <div class="hero-actions">
    <a class="button-primary" href="mailto:w.nathaniel.s@gmail.com">Email</a>
    <a class="button-secondary" href="https://scholar.google.com/citations?user=mZn8X9UAAAAJ&hl=en">Google Scholar</a>
    <a class="button-secondary" href="https://orcid.org/0000-0002-8749-2188">ORCID</a>
    <a class="button-secondary" href="https://github.com/nathanielwei">GitHub</a>
  </div>
</section>

---

## Education

* **Ph.D., Information Engineering** — The Chinese University of Hong Kong, Aug 2018 – Jul 2023  
  MMLab; advisors: Prof. Xiaoou Tang, Prof. Dahua Lin  
  *Thesis:* [Deep Learning for Predicting Real-World Outcomes](/publication/2023-01-01-deep-learning-for-predicting-real-world-outcomes)

* **M.Phil., Applied Mathematics** — The Hong Kong Polytechnic University, Jan 2014 – May 2017  
  Advisors: Prof. Heung Wong, Prof. Cedric Ka-Fai Yiu

* **B.A., Finance and Banking** — Shenzhen University, Sep 2009 – Jun 2013  
  Outstanding Graduate (rank 1/405); GPA 3.9/4.0

---

## Experience

* **Quantitative AI Researcher** — Present  
  End-to-end deep learning, adaptive factor modeling, market regime detection, and event-driven prediction. Working with Prof. Jian Guo on [Janus-Q](/publication/2026-02-23-janus-q-end-to-end-event-driven-trading-via-hierarchical-gated-reward-modeling) and [FinKario](/publication/2025-08-01-finkario-event-enhanced-automated-construction-of-financial-knowledge-graph).

* **Analyst, Investment** — Top-tier hedge fund, Hong Kong SAR, Sep 2024 – Mar 2025  
  Multi-market monitoring, event-driven backtesting, global factor data integration (Bloomberg/Barra).

* **Quantitative Researcher** — Top-tier asset management firm, mainland China, May 2022 – Sep 2024  
  Deep learning strategies for CSI 300/800 and mid/small-cap indices; led quant AI platform development. Models include [HireVAE](/publication/2023-08-01-hirevae-an-online-and-adaptive-factor-model) and multi-agent GPT factor discovery.

* **Research Intern** — SenseTime Group Limited, Hong Kong SAR, Feb – Jul 2018  
  TCN/LSTM for financial futures; RL environment for limit order book data.

* **Research Assistant** — The Hong Kong Polytechnic University, Apr 2017 – Feb 2018  
  Deep learning jump detection across 11 global indices; regime-switching on high-frequency data.

---

## Publications

*Selected work in quantitative finance and AI. Full list: [Publications](/publications/) · [Google Scholar](https://scholar.google.com/citations?user=mZn8X9UAAAAJ&hl=en).*

<ul class="cv-publications">
{% assign sorted_pubs = site.publications | sort: 'date' | reverse %}
{% for post in sorted_pubs %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

---

## Skills

| Area | Details |
|------|---------|
| **Quant AI** | End-to-end investment systems, factor models, regime detection, event-driven signals |
| **Deep Learning** | PyTorch; graph attention, VAE, reinforcement learning |
| **Programming** | Python, SQL, R, Matlab, C++ |
| **Financial Data** | Bloomberg, Barra, WIND, FactSet, Refinitiv |

---

## Honors & Awards

* 2023 — China Merchants Group New Star Training Camp, Outstanding Individual
* 2019 — CUHK-SenseTime Joint Lab Excellent Contribution Award
* 2018–2023 — Postgraduate Studentship, CUHK
* 2015 — Teaching Postgraduate Studentship, PolyU
* 2013 — Outstanding Graduate, Shenzhen University (1st in Finance & Banking)
* 2012 — National Postgraduate Recommendation (examination waived)
