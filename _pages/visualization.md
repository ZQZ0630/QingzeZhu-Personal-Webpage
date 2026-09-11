---
layout: single
title: "Interactive Visualization Showcase "
permalink: /visualization/
author_profile: true
---

This page presents the deliverables from my faculty-supervised research on teaching technology, demonstrating my ability to translate statistical concepts into interactive computational tools

## Unified Distribution Explorer

**What it is.**
An interactive explorer for the common probability distributions (Bernoulli, Binomial, Poisson, Normal, and others). Each distribution shows its PMF/PDF formula, parameters and support, a live plot of the density and CDF, a probability table, and a calculator that prints the matching R code for every quantity it returns — so the tool doubles as a code reference for students.

**How to use it.**

1. Pick a distribution from the **Distributions** menu.
2. Move the **parameter** sliders and watch the plot, the properties panel, and the probability table update together.
3. Use the **Calculator** to evaluate P(X = x), P(X ≤ x), or a quantile; each result is shown alongside the R call that produces it.
4. Where a distribution has a process view — Poisson, for instance — switch to the second tab to see it.

👉 [Open the Unified Distribution Explorer](https://pages.stat.wisc.edu/~byang/STAT311/unified_distribution_explorer.html){: .btn .btn--primary}

*Deployed on the STAT 311 course site at UW–Madison.*

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
