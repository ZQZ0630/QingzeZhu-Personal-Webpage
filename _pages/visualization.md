---
layout: single
title: "Visualization Projects"
permalink: /visualization/
author_profile: true
---

This page collects some of my interactive visualization projects related to probability, statistics, and applied modeling. I am gradually extending these tools and using them as teaching and learning resources.

## Probability Distributions Map

<figure style="text-align: center;">
  <a href="{{ site.baseurl }}/probability_map/">
    <img src="{{ site.baseurl }}/images/probability-map-preview.png"
         alt="Preview of the Probability Distributions Map interface"
         style="max-width: 100%; border: 1px solid #ddd; border-radius: 6px;">
  </a>
  <figcaption style="margin-top: 8px; font-size: 0.9rem; color: #666;">
    Preview of the interactive Probability Distributions Map. Click the image to open the full tool.
  </figcaption>
</figure>

The **Probability Distributions Map** is an interactive tool that helps students connect common probability distributions to their:

- formulas (PDFs/PMFs),
- parameters and their interpretations, and
- typical modeling scenarios.

The map organizes distributions (e.g., Bernoulli, Binomial, Poisson, Normal, etc.) as nodes and links, so that students can see how they are related (for example, Bernoulli as a building block for Binomial, or Poisson as a limiting case).

👉 [Open the Probability Distributions Map]({{ site.baseurl }}/probability_map/){: .btn .btn--primary}

Each node links to a minimal HTML module that contains:

- the core formula and notation,
- explanations of parameter roles,
- a short description of when the distribution is used, and
- interactive elements for selected distributions (e.g., changing parameters and seeing the shape update).

The goal is to provide a structured “map” so that students can gain big-picture intuition before diving into detailed proofs or derivations.

---

## Future visualization work

I plan to add more visualization projects here, including:

- interactive demonstrations of Brownian Motion and Geometric Brownian Motion,
- visual explanations of sampling schemes and sampling bias,
- dashboards that link agricultural development indicators to rural incomes.
