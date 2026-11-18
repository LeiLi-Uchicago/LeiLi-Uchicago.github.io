---
layout: "post"
title: "Biological Context Matters in Single-cell QC"
date: "2026-10-13 01:43:59 +0000"
categories: ["thoughts"]
tags: ["single-cell", "computational-biology", "verification"]
description: "Good QC isn’t just about removing low-quality cells. It’s also about knowing what you’re keeping — and what you might be losing."
linkedin: "https://www.linkedin.com/feed/update/urn:li:activity:7515588114703343616/"
---

A great example of why bioinformaticians need to understand the biological context behind their data, rather than just follow a standard pipeline.

In practice, we use a combination of a dataset-dependent threshold (e.g., the 98th percentile) and a fixed cutoff (e.g., 10% ), taking the more stringent of the two for each sample.

We implemented this approach in our LinQ-View paper. BTW, The 98th percentile and 10% cutoff are just our defaults for PBMC data, and both are adjustable.

Interestingly, this also gives us a useful warning signal: if a sample ends up hitting that 10% ceiling, I take it as a reminder to double-check what’s going on.

And here’s one simple trick I always recommend: plot violin plots of nCount, nFeature, and **percent.mt** before and after QC.

It only takes a few seconds to glance at them, but it can save you from accidentally throwing away biologically meaningful cells.

Good QC isn’t just about removing low-quality cells. It’s also about knowing what you’re keeping — and what you might be losing.

---

*Reposted source: [Alessandro De Santis on mitochondrial QC thresholds](https://www.linkedin.com/feed/update/urn:li:share:7515479168562896897/).*
