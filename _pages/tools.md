---
layout: archive
permalink: /tools/
author_profile: true
toc: true
feature_row_app1:
  - image_path: Wald.png
    alt: "Wald test"
    url: "https://chadmilando.com/wald-test-percentiles/"
    title: "Wald test percentiles"
    excerpt: "Johnson and Romer 2016 provided an algorithm to compare a limited set of percentiles between two distributions. I created an R function to implement it."
    btn_label: "View"
    btn_class: "btn--inverse"
  - image_path: DLNM_sweep.png
    alt: "DLNM sweep"
    url: "https://chadmilando.com/dlnm-sweep/"
    title: "DLNM parameter sweep"
    excerpt: "These functions allow you to test many crossbasis options in the DLNM framework."
    btn_label: "View"
    btn_class: "btn--inverse"
---

This page lists software and tools I have built, as well as one-off code functions that I think could be useful.

{% include toc %}
<br>
# Software / Tools
___
## Simulation of infectious disease dynamics
[This document](https://mobslab.shinyapps.io/simulate_infection_data/) walks through the steps of simulating estimates of the instantaneous reproduction number,$R(t)$, which can be helpful for surveillance and intervention planning of infectious diseases. For this simulation, we take several steps to simulate how cases spread from one person to another: (1) Simulate the individual-level incubation time distribution, then (2) simulate the individual-level transmission time distribution (assumed to be independent from the incubation time distribution). We then can derive distributions for the generation time and serial interval using the relationships, simulate the individual-level administrative delay in reporting, and simulate the population-level infectivity dynamics.

[![RtEval](/assets/images/RtEval.png)](https://mobslab.shinyapps.io/simulate_infection_data/)

## R package: `WhiteLabRt`

[This R package](https://cran.r-project.org/web/packages/WhiteLabRt/index.html) contains a collection of functions related to novel methods for estimating R(t), created by the lab of Professor Laura White. Currently implemented methods include two-step Bayesian back-calculation and now-casting for line-list data with missing reporting delays, adapted in 'STAN' from [Li (2021)](doi:10.1371/journal.pcbi.1009210), and calculation of time-varying reproduction number assuming a flux between various adjacent states, adapted into 'STAN' from [Zhou (2021)](doi:10.1371/journal.pcbi.1010434).

[![WhiteLabRt](/assets/images/WhiteLabRt.png)](https://cran.r-project.org/web/packages/WhiteLabRt/index.html)

## Macro for Compilation of Report-backs (MCR)

[This repository](https://github.com/cmilando/reportback-vba) contains the code for the Macro for Compilation of Report-backs (MCR), an open-source, generalizable tool designed to provide researchers in health studies with a flexible and scalable method for compiling individual reports. If you use MCR in your projects, please cite [Polka et. al., 2021](https://doi.org/10.3390/ijerph18116104). Let me know if you have any questions! 

[![MCR](/assets/images/MCR.png)](https://github.com/cmilando/reportback-vba)

## Framework for Rapid Exposure and Health Effects Estimation (FRESH-Est)

The Framework for Rapid Exposure and Health Effects Estimation (FRESH-Est) is a tool that allows users to estimate the health affects attributable to point source emissions. The tool combines dispersion modeling (AERMOD) with calculations of attributable burden (similar to the EPA’s BenMAP program) in a single framework. The benefits of using FRESH-Est are: 1) health effects for various emissions scenarios can be estimated quickly, and 2) there is an optimization module that focuses on receptor concentrations, health effects, or inequality impacts. See the [Milando, Martenies, and Batterman, 2016](https://doi.org/10.1016/j.envint.2016.06.005) for more details. A working demo is also available in [this google folder](https://drive.google.com/drive/folders/10FAlCxDc57wwkE5jNLcrf3qc4bGVUkso?usp=sharing) (access available upon request). 

[![FRESHEST](/assets/images/FRESHEST.jpg)](https://doi.org/10.1016/j.envint.2016.06.005)

## Two-stage synthetic population generation via combinatorial optimization

We built on Combinatorial Optimization code by Dr. Paul Williamson ([link](https://pcwww.liv.ac.uk/~william/microdata/CO%20070615/CO_software.html)) to create synthetic cohorts for various populations in Boston. These synthetic cohorts have been used in a number of applications at BU: to assess the relationship between smoking and demographic variables in New Bedford, MA ([Levy et. al., 2014](https://doi.org/10.1371/journal.pone.0087144)), to assess impacts of multiple health promoting behaviors (diet, exercise) in combination with environmental exposures ([Basra et. al., 2017](https://doi.org/10.3390/ijerph14070730)), and testing the impact of neighborhood greening on birthweight ([Milando et. al., 2021](https://doi.org/10.1038/s41370-021-00318-4)). A summary of the methods and current applications are described [here](https://chadmilando.com/synthpop-bookdown/).

[![SYNTHPOP](/assets/images/synthpop.png)](https://chadmilando.com/synthpop-bookdown/)

## miniCONTAM rapid indoor air health impact estimation 

_In progress_

[This document](https://contam-prj-build-doc.readthedocs.io/en/latest/index.html) describes how to set up CONTAM models.

## CONTAM Energy-plus automated coupled model preparation

_In progress_

# Functions
___
{% include feature_row id="feature_row_app1" %}