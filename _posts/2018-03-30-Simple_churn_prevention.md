---
layout: post
title: Simple Churn Prevention
subtitle:
tags: [marketing]
---

Online retailers have a difficult time measuring a single customer's activity level.  There are "one and done" who make a single purchase. Some customers establish an intense purchase pattern over  a short period and then quickly move on.  Still others may purchase infrequently, but steadily, and stay "loyal" for a longer period. It can be hard to keep track of which customers are active.

Many prediction companies offer churn prevention algorithms out of the box for a small fee - but savvy companies can establish simple algorithms that achieve similar results on their own.  

In a period of 5-6 hours, me and two colleagues put together the following recommendation to a ride share company on how it could prevent churn.  

Steps:
1. Establish a churn metric
2. Fit a classification model to determine which customers advance toward the metric most quickly.
3. If a model candidate fits predicts well, commit to a controlled experiment.
4. Each week, as customers' probability of churning increases past a threshold, assign them to a test or control group.
5. Provide a "winback offer" to the test group.
6. At the end of the time (or when the populations in test and control provide enough power for a hypothesis test), evaluate the model's predictive power and the offer's ability to win customers back.
