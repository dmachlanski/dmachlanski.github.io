---
title: "Robustness of Algorithms for Causal Structure Learning to Hyperparameter Choice"
collection: publications
category: conferences
permalink: /publication/2024-03-15-robustness-structure-learning
excerpt: 'Investigating robustness of causal discovery methods to (bad) hyperparameter selection.'
date: 2024-03-15
venue: 'Third Conference on Causal Learning and Reasoning (CLeaR)'
paperurl: 'https://proceedings.mlr.press/v236/machlanski24a.html'
citation: 'Machlanski, D., Samothrakis, S., Clarke, P. (2024). &quot;Robustness of Algorithms for Causal Structure Learning to Hyperparameter Choice.&quot; <i>Proceedings of the Third Conference on Causal Learning and Reasoning</i>. PMLR 236:703-739.'
---
Hyperparameters play a critical role in machine learning. Hyperparameter tuning can make the difference between state-of-the-art and poor prediction performance for any algorithm, but it is particularly challenging for structure learning due to its unsupervised nature. As a result, hyperparameter tuning is often neglected in favour of using the default values provided by a particular implementation of an algorithm. While there have been numerous studies on performance evaluation of causal discovery algorithms, how hyperparameters affect individual algorithms, as well as the choice of the best algorithm for a specific problem, has not been studied in depth before. This work addresses this gap by investigating the influence of hyperparameters on causal structure learning tasks. Specifically, we perform an empirical evaluation of hyperparameter selection for some seminal learning algorithms on datasets of varying levels of complexity. We find that, while the choice of algorithm remains crucial to obtaining state-of-the-art performance, hyperparameter selection in ensemble settings strongly influences the choice of algorithm, in that a poor choice of hyperparameters can lead to analysts using algorithms which do not give state-of-the-art performance for their data.