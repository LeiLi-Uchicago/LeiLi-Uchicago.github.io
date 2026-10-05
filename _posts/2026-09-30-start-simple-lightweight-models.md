---
layout: post
title: "Start Simple: Why Lightweight Models Still Matter"
subtitle: "A simpler model can reveal what information a more complex model actually needs."
date: 2026-09-30
categories:
  - thoughts
tags:
  - Machine Learning
  - Scientific AI
  - Biological Discovery
  - Interpretability
description: "Simple models are not only baselines. Their successes and failures can reveal which biological structure or information a more complex model truly needs to capture."
linkedin: https://www.linkedin.com/posts/lei-li-46713b78_deep-learning-based-gene-perturbation-effect-activity-7507590367249207297-BtSM
---

There is a tendency in modern machine learning to jump quickly toward more complex models.

Sometimes that is justified.

But in biological discovery, I think lightweight methods still have enormous value.

A simpler model is not only a baseline.

Its failure mode can be informative.

Suppose a relatively simple model performs surprisingly well.

That tells us that the signal may already be captured by straightforward structure in the data.

The more complex model then needs to justify itself by adding something genuinely new.

Now consider the opposite case.

A simple model fails, but a more complex model succeeds.

That difference can help reveal what additional information the complex model is capturing.

Maybe it is nonlinear structure.

Maybe it is context dependence.

Maybe it is an interaction between features.

Maybe the representation itself is the important contribution.

This is especially useful in biology.

The goal is often not only to maximize predictive performance.

We also want to understand:

- what information matters,
- what biological structure is being captured,
- why the model improves,
- and whether that improvement changes our interpretation of the system.

A complex model that improves a benchmark by a few percentage points may be useful.

But a model that reveals **why** the simpler approach fails can be much more scientifically interesting.

This is one reason I think "start simple" remains a strong strategy.

Use a lightweight method first.

Understand what it captures.

Understand where it breaks.

Then ask what biological structure the next model must add.

That creates a more informative progression than simply moving from simple to complex because complexity is available.

In scientific machine learning, performance matters.

But understanding **what new information the model contributes** may matter just as much.
