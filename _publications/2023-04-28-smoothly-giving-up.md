---
title: "Smoothly Giving Up: Robustness for Simple Models"
collection: publications
permalink: /publication/2023-04-28-smoothly-giving-up.md
excerpt: 'Boosting with $\alpha$-loss and its application to simple models'
date: 2023-04-28
venue: 'AISTATS 2023'
paperurl: 'http://academicpages.github.io/files/smoothly_giving_up.pdf'
citation: 'Your Name, You. (2009). &quot;Smoothly Giving Up: Robustness for Simple Models&quot; <i>Journal 1</i>. 1(1).'
---
There is a growing need for models that are interpretable and have reduced energy/computational cost (e.g., in health care analytics and federated learning). Examples of algorithms to train such models include logistic regression and boosting. However, one challenge facing these algorithms is that they provably suffer from label noise; this has been attributed to the joint interaction between oft-used convex loss functions and simpler hypothesis classes, resulting in too much emphasis being placed on outliers. In this work, we use the margin-based $\alpha$-loss, which continuously tunes between canonical convex and quasi-convex losses, to robustly train simple models. We show that the $\alpha$ hyperparameter smoothly introduces non-convexity and offers the benefit of “giving up” on noisy training examples. We also provide results on the Long-Servedio dataset for boosting and a COVID-19 survey dataset for logistic regression, highlighting the efficacy of our approach across multiple relevant domains. 

[Download paper here](http://academicpages.github.io/files/smoothly_giving_up.pdf)
