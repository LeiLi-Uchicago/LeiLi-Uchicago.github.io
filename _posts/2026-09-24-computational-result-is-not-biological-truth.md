---
layout: post
title: "A Computational Result Is Not Biological Truth"
subtitle: "Successful computation is not the same as scientific validation."
date: 2026-09-24
categories:
  - thoughts
tags:
  - Scientific AI
  - Computational Biology
  - Biological Interpretation
  - Verification
description: "An algorithm can produce a technically valid and visually convincing result while the biological interpretation built on top of it is still unsupported."
linkedin: https://www.linkedin.com/posts/lei-li-46713b78_in-my-last-post-i-wrote-about-why-ai-has-activity-7498196222667608064-Wbwc
---

A computational result is not necessarily biological truth.

This distinction has always mattered in computational biology, but it becomes even more important as AI makes sophisticated analyses easier to run.

Consider a simple example from single-cell analysis.

Suppose we have T cells and NK cells in a PBMC dataset. These populations can be transcriptionally close, and a trajectory algorithm may have no difficulty constructing a smooth path between them.

The computation can be perfectly valid.

The input satisfies the requirements. The algorithm runs successfully. The trajectory looks clean and visually convincing.

But that does not establish a developmental lineage between T cells and NK cells.

**A computational trajectory is not necessarily a biological trajectory.**

The problem is not always that the algorithm made a computational mistake.

The more subtle failure can happen one step later:

**valid computation → unsupported biological interpretation**

This is important because computational tools are designed to answer the mathematical question we give them. If the inputs are valid, many algorithms will produce an answer.

That does not mean we asked the right biological question.

The same issue appears in many analyses:

- trajectory inference,
- pathway enrichment,
- cell-cell communication,
- regulatory-network inference,
- clustering,
- differential-expression analysis.

Each method can produce a technically valid result while the scientific interpretation still requires domain knowledge, external evidence, and biological judgment.

**Successful computation is not validation.**

This problem existed long before LLMs.

What AI changes is the scale.

AI can now make it much easier to run many analyses, connect them together, and generate a polished interpretation. That increases productivity, but it can also allow an unsupported assumption to propagate much farther before anyone notices.

Sometimes the most dangerous scientific errors are not obvious computational failures.

They are **interpretation errors built on perfectly valid computations**.

That is why scientific AI cannot be evaluated only by asking whether the workflow ran successfully.

We also need to ask whether the biological claim is actually supported.
