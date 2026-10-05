---
layout: post
title: "AI Knew the Biology. Why Didn't It See the Mistake?"
subtitle: "Knowing something is not the same as knowing when that knowledge matters."
date: 2026-10-03
categories:
  - thoughts
tags:
  - Scientific AI
  - Single-Cell
  - Biological Reasoning
  - Verification
description: "In a PBMC annotation experiment, AI systems had the biological knowledge needed to identify suspicious labels, but often failed to retrieve and apply it until explicitly prompted."
linkedin: https://www.linkedin.com/posts/lei-li-46713b78_ai-knew-the-biology-why-didnt-it-see-the-activity-7498894660698910720-ArNR
---

I recently ran a small experiment that made me think differently about what it means for AI to "know" biology.

I gave several AI agents the same single-cell PBMC visualization and asked them to identify what looked wrong.

The plot contained several biological red flags that an experienced immunologist would likely inspect quickly.

For example:

- a CD8+ naive T-cell population was unusually far from the other T-cell populations,
- B cells appeared immediately next to major T-cell populations,
- a CD4+ naive T-cell population sat in an unexpected monocyte/NK region,
- and NK cells appeared mixed with CD14+ monocytes.

The agents did notice some issues.

But they also spent a surprising amount of effort discussing generic possibilities: marker limitations, visualization choices, overlapping populations, lack of ground truth, and other reasonable caveats.

What was interesting was what happened when I became more specific.

In one case, I asked:

**Could B and CD8 T be swapped?**

The AI immediately recognized the biological inconsistency.

It explained the expected biology, identified the relevant markers, and described exactly how the annotation should be checked.

So the biological knowledge was clearly there.

The model did not need to learn anything new.

It needed to apply knowledge it already possessed to the right part of the problem.

That suggests an important distinction:

**hypothesis generation / anomaly detection**

versus

**hypothesis verification**

Once the correct hypothesis was proposed, verification was relatively easy.

The harder step was deciding which possibility deserved attention in the first place.

This may be one of the more important limitations of current scientific AI systems.

The problem is not always:

> Does the model know the relevant biology?

Sometimes the harder question is:

> Does the model know that this is the biology that matters right now?

**The AI possessed the relevant knowledge. It failed to retrieve and apply it at the right moment.**

And that leads to a broader point:

**Knowing something is not the same as knowing when that knowledge matters.**
