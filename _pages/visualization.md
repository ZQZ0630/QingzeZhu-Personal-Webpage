---
layout: single
title: "Interactive Visualization Showcase "
permalink: /visualization/
author_profile: true
---

This page presents the deliverables from my faculty-supervised research on teaching technology, demonstrating my ability to translate statistical concepts into interactive computational tools

## Unified Distribution Explorer

<figure style="text-align: center;">
  <a href="https://pages.stat.wisc.edu/~byang/STAT311/unified_distribution_explorer.html">
    <img src="{{ site.baseurl }}/images/distribution-explorer-preview.png"
         alt="The Unified Distribution Explorer showing the binomial distribution"
         style="max-width: 100%; border: 1px solid #ddd; border-radius: 6px;">
  </a>
  <figcaption style="margin-top: 8px; font-size: 0.9rem; color: #666;">
    Click the image to open the Unified Distribution Explorer.
  </figcaption>
</figure>

**What it is.**
A single-page explorer for the common probability distributions, deployed on the STAT 311 course site at UW–Madison. One screen holds everything a student needs for a given distribution: its formula, its properties evaluated at the current parameters, a plot, a probability table, and a calculator that shows the R code behind every number it returns.

**How to use it.**

1. Choose a distribution from the **Distributions** menu at the top left. A one-line description tells you what it models.
2. Set the **parameters** with the sliders, or type exact values into the boxes beside them. Everything else on the page recomputes as you move them.
3. Read the **Properties** panel for support, mean, variance, and — where they exist — special cases and approximations (for example, that Bin(n, p) approaches Pois(np) when n is large and np small). The **Reset** button returns the defaults.
4. Use the **Visualization** checkboxes to overlay the PMF/PDF and the CDF on the same axes, and lock the axes when you want two parameter settings to be visually comparable.
5. In **Calculator with R code**, move the *Cutoff* slider for P(X = x) and P(X ≤ x), or the *Left prob* slider for quantiles. Each result is printed with the R call that produces it — `dbinom`, `pbinom`, `qbinom`, and so on — so the page works as a code reference as well as a visual one.
6. The **PMF table** lists the distribution term by term; *Pop out* opens it in its own window for side-by-side reading.

👉 [Open the Unified Distribution Explorer](https://pages.stat.wisc.edu/~byang/STAT311/unified_distribution_explorer.html){: .btn .btn--primary}

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
