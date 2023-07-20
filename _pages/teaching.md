---
layout: archive
permalink: /teaching/
author_profile: true
toc: true
---

This page lists teaching tools in Excel, R, and Python, as well as pdfs of presentations I've given on topics relevant to environmental health and epidemiology, engineering and introductions to computer science.

{% include toc %}
<br>
# Methods
___
## B-spline functions

Basis-splines are an essential part of many computer science functions, but what are they and how do they work? I developed a [google sheet](https://docs.google.com/spreadsheets/d/1E8ozpvn5O1euQtNcaiMLqa-QP4Q_PBpoAX7TgeKYCkU/edit?usp=sharing) to walk through the Cox-de Boor recursion implementation of cubic b-splines with one knot.

[![B-spline functions](/assets/images/Bspline_thumb.PNG)](https://docs.google.com/spreadsheets/d/1E8ozpvn5O1euQtNcaiMLqa-QP4Q_PBpoAX7TgeKYCkU/edit?usp=sharing)

## Conditional and Unconditional Poisson regression

Unconditional Poisson models may be computationally expensive to run in case-crossover settings with discrete outcomes. [Armstrong, Gasparrini, and Tobias, 2014](https://bmcmedresmethodol.biomedcentral.com/articles/10.1186/1471-2288-14-122) show that conditional Poisson is simpler and produces the same results. I recreated the similarity between the conditional and unconditional poisson models for case-crossover epidemiology, in a [google sheet](https://docs.google.com/spreadsheets/d/1eNbHk5S-NEwsu49rO7XXXCVJnmLdLUQRxH3OQ-5HwUU/edit?usp=sharing), with Solver used to minimize the log-likelihood function.

[![Poisson](/assets/images/Poisson.png)](https://docs.google.com/spreadsheets/d/1eNbHk5S-NEwsu49rO7XXXCVJnmLdLUQRxH3OQ-5HwUU/edit?usp=sharing) 

## Distributed Lag Non-linear Modeling (DLNM)

DLNMs are ubiquitous in time-series studies of the health impact of environmental hazards, because they allow for simultaneous modeling of exposures and lag structures of those exposures (e.g., what happened yesterday and today differently impacts the probability of health outcomes today). The methods underlying DLNMs are somewhat complex (e.g., creation of crossbasis and prediction matrices), so I created a [google sheet](https://docs.google.com/spreadsheets/d/1SP6PTXO6TtaVxoACTi5at0KpCNa9jmGhb6vR4PSiYmg/edit?usp=sharing]) that walks through each of the steps of DLNM application. The seminal reference for DLNMs is [Gasparrini, 2013](https://onlinelibrary.wiley.com/doi/full/10.1002/sim.5963)

[![DLNM](/assets/images/DLNM.png)](https://docs.google.com/spreadsheets/d/1SP6PTXO6TtaVxoACTi5at0KpCNa9jmGhb6vR4PSiYmg/edit?usp=sharing) 

# Presentations
____

