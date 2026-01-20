---
layout: single
title: "Interactive Visualization Showcase "
permalink: /visualization/
author_profile: true
---

This page presents the deliverables from my faculty-supervised research on teaching technology, demonstrating my ability to translate statistical concepts into interactive computational tools

## Probability Distributions Map

<figure style="text-align: center;">
  <a href="{{ site.baseurl }}/probability_map/">
    <img src="{{ site.baseurl }}/images/probability-map-preview.png"
         alt="Preview of the Probability Distributions Map interface"
         style="max-width: 100%; border: 1px solid #ddd; border-radius: 6px;">
  </a>
  <figcaption style="margin-top: 8px; font-size: 0.9rem; color: #666;">
    Click the image to open the Probability Distributions Map.
  </figcaption>
</figure>

**What it is.**  
An interactive “map” of common probability distributions (e.g., Bernoulli, Binomial, Poisson, Normal). Each node links to a small page with formulas, parameter meanings, and typical use cases.

**How to use it.**

1. Start on the map and **click a distribution node** (for example, *Normal*, *Binomial*, or *Poisson*).  
2. On the distribution page, **read the short description** of when the distribution is used and what its parameters mean.  
3. Where available, use **sliders or input boxes** to change parameters and see how the graph and notation change.  
4. Use the navigation links to **go back to the map** and compare another distribution.

👉 [Open the Probability Distributions Map]({{ site.baseurl }}/probability_map/){: .btn .btn--primary}

---

## Brownian Motion Laboratory

<figure style="text-align: center;">
  <a href="{{ site.baseurl }}/brownian_lab.html">
    <img src="{{ site.baseurl }}/images/brownian-lab-preview.png"
         alt="Preview of the Brownian Motion Laboratory interface"
         style="max-width: 100%; border: 1px solid #ddd; border-radius: 6px;">
  </a>
  <figcaption style="margin-top: 8px; font-size: 0.9rem; color: #666;">
    Click the image to open the Brownian Motion Laboratory.
  </figcaption>
</figure>

**What it is.**  
An interactive lab that connects discrete random walks to Brownian motion and related continuous-time processes. The landing page has three cards: *Discrete Random Walk*, *Donsker’s Bridge*, and *Stochastic Processes*.

**Quick start (3 steps).**

1. On the landing page, **click a module card** (e.g., *Discrete Random Walk* or *Stochastic Processes*).  
2. In the control panel, **choose a model and set parameters** such as number of paths, steps, speed, and random seed.  
3. Click **Play / Start** (or move the time slider) and watch the **left plot** (sample paths) and **right panel** (distributions / statistics) evolve over time.

**What you can explore.**

- In *Discrete Random Walk*, draw many paths, add **time slices**, and inspect cross-sectional histograms (mean, variance, etc.).  
- In *Donsker’s Bridge*, see how scaled random walks \(W_n(t) = S_{\lfloor nt \rfloor}/\sqrt{n}\) converge toward Brownian motion.  
- In *Stochastic Processes*, compare models such as Brownian Motion, Poisson, Ornstein–Uhlenbeck, Geometric Brownian Motion, and CIR by changing parameters and observing both paths and terminal distributions.

👉 [Open the Brownian Motion Laboratory]({{ site.baseurl }}/brownian_lab.html){: .btn .btn--primary}
