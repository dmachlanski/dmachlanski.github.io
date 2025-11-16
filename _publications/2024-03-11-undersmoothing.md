---
title: "Undersmoothing Causal Estimators With Generative Trees"
collection: publications
category: manuscripts
permalink: /publication/2024-03-11-undersmoothing
excerpt: 'Using Generative Trees to generate new samples and undersmooth downstream causal estimators.'
date: 2024-03-11
venue: 'IEEE Access'
slidesurl: #'https://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10466753'
bibtexurl: #'https://academicpages.github.io/files/bibtex1.bib'
citation: 'Machlanski, D., Samothrakis, S., Clarke, P. (2024). &quot;Undersmoothing Causal Estimators With Generative Trees.&quot; <i>IEEE Access</i>. vol. 12, pp. 38562-38574.'
---
Average causal effects are averages of (heterogeneous) individual treatment effects (ITEs) taken over the entire target population. The estimation of average causal effects has been studied in depth, but averages are insufficient for more individualised decision-making where ITEs are more appropriate. However, estimating ITEs for every population member is challenging, particularly when estimation must be based on observational data rather than data from randomised experiments. One potential problem with observational data arises when there are large differences between the sample distributions of the input features of the treated and control units. This problem is known as covariate shift. It can lead to model misspecification the harmful effects of which can be severe for ITE estimation because point estimation is highly sensitive to regions of the common support of the input space in which the number of treated or control units is very small. Moreover, common solutions are often based on reweighing schemes involving propensity scores which were originally designed for average effects and not ITEs. In this paper, we propose Debiasing Generative Trees, a novel data augmentation method based on generative trees that debiases and undersmooths causal estimators trained on augmented data. It encourages higher modelling complexity that reduces misspecification and improves estimation of ITEs. We show empirically that our proposed approach yields models of higher complexity and more accurate predictions of ITEs, and is competitive with traditional methods for estimating average treatment effects. Our results confirm that reweighing methods can struggle with ITE estimation and that the choice of model class can significantly impact prediction performance.