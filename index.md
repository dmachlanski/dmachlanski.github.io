---
layout: default
title: Home
redirect_from:
  - /about/
  - /about.html
---

<img class="portrait" src="{{ '/images/profile.jpg' | relative_url }}" alt="Photo of Damian Machlanski" width="480" height="632">

I am a Research Associate in Causal AI at the [University of Edinburgh](https://www.ed.ac.uk/) and a Postdoctoral Fellow at the [Causality in Healthcare AI Hub (CHAI)](https://www.chai.ac.uk/).

I am interested in all things related to causality, including mathematical theory, statistical methods, applications with real data, and the overarching philosophy around it. My research often intersects with machine learning and observational data, which has led to my specific interests in causal discovery and causal effect estimation, as well as domain generalisation and model selection. Since joining CHAI, I have also been applying these methods to healthcare datasets, which are often temporal in nature.

Before moving to Edinburgh, I obtained my PhD in Computer Science at the University of Essex, supervised by Dr Spyros Samothrakis and Prof. Paul Clarke. Before my PhD, I worked as a software developer for several years, and I still enjoy programming in my work.

<p class="links">
{%- for link in site.links %}
  <a href="{{ link.url }}">{{ link.title }}</a>
{%- endfor %}
</p>

## News

- My last PhD paper, on the challenges of hyperparameter tuning for causal effect estimation, is out in [Machine Learning](https://doi.org/10.1007/s10994-026-07140-9).
- New paper on explainable AI for transparent predictive risk models with health data accepted at [JMIR](https://doi.org/10.2196/105364).
- Our tutorial on time series causal discovery has been accepted at IEEE Signal Processing Magazine (forthcoming; [preprint](https://arxiv.org/abs/2610.13430)).
- Our work on causal actionable prediction models in psychosis is out in [BJPsych](https://doi.org/10.1192/bjp.2026.10561).
- Our paper on causal ordering for time series causal discovery has been accepted at [TMLR](https://openreview.net/forum?id=hWuTzqggSd).
- Workshop: [Bridging Perspectives: Engaging with Causality Across Research Sectors](https://www.eventbrite.co.uk/e/bridging-perspectives-engaging-with-causality-across-research-sectors-tickets-1851174957129), Edinburgh.
