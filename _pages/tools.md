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
---

This page lists software and tools I have built, as well as one-off code functions that I think could be useful.

{% include toc %}
<br>
# Software
___
## Macro for Compilation of Report-backs (MCR)

[This repository](https://github.com/cmilando/reportback-vba) contains the code for the Macro for Compilation of Report-backs (MCR), an open-source, generalizable tool designed to provide researchers in health studies with a flexible and scalable method for compiling individual reports. If you use MCR in your projects, please cite [Polka et. al., 2021](https://doi.org/10.3390/ijerph18116104). Let me know if you have any questions! 

[![MCR](/assets/images/MCR.png)](https://github.com/cmilando/reportback-vba)

## Framework for Rapid Exposure and Health Effects Estimation (FRESH-Est)

The Framework for Rapid Exposure and Health Effects Estimation (FRESH-Est) is a tool that allows users to estimate the health affects attributable to point source emissions. The tool combines dispersion modeling (AERMOD) with calculations of attributable burden (similar to the EPA’s BenMAP program) in a single framework. The benefits of using FRESH-Est are: 1) health effects for various emissions scenarios can be estimated quickly, and 2) there is an optimization module that focuses on receptor concentrations, health effects, or inequality impacts. See the [Milando, Martenies, and Batterman, 2016](https://doi.org/10.1016/j.envint.2016.06.005) for more details. A working demo is also available in [this google folder](https://drive.google.com/drive/folders/10FAlCxDc57wwkE5jNLcrf3qc4bGVUkso?usp=sharing) (access available upon request). 

[![FRESHEST](/assets/images/FRESHEST.jpg)](https://doi.org/10.1016/j.envint.2016.06.005)

## Two-stage synthetic population generation via combinatorial optimization

_In progress_ (FJBI bookdown)

## miniCONTAM rapid indoor air health impact estimation 

_In progress_

## CONTAM Energy-plus automated coupled model preparation

_In progress_

# Functions
___
{% include feature_row id="feature_row_app1" %}