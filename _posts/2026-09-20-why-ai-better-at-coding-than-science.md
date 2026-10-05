---
layout: post
title: "Why Is AI So Much Better at Coding Than at Science?"
subtitle: "Coding has cheap verifiers. Science often does not."
date: 2026-09-20
categories:
  - thoughts
tags:
  - Scientific AI
  - AI Agents
  - Verification
  - Scientific Reasoning
description: "AI performs especially well in coding partly because code has cheap and immediate verifiers. Scientific reasoning often lacks equally fast and reliable feedback."
linkedin: https://www.linkedin.com/posts/lei-li-46713b78_earlier-this-week-our-group-had-a-thought-provoking-activity-7496382997869338624-zQq6
---

Why are people increasingly comfortable letting AI agents write code, while remaining much more cautious about hypothesis generation, biological interpretation, and scientific reasoning?

One reason is obvious: coding is highly structured.

Programming languages have explicit syntax. Inputs and outputs are formalized. The environment is largely human-created and machine-readable.

But I think there is another reason that matters even more.

**Coding has cheap verifiers.**

A coding agent can generate code and immediately ask:

- Does it compile?
- Does it run?
- Does it throw an error?
- Do the unit tests pass?
- Does the output match the expected behavior?

That creates a natural closed loop:

**generate → execute → test → correct**

The agent does not need to rely only on its own confidence.

The environment gives it feedback.

Science is very different.

A scientific hypothesis can be coherent, well written, statistically supported, and still be wrong.

A biological interpretation can sound completely reasonable while depending on an invalid assumption.

A computational workflow can finish successfully without ever encountering a runtime error, even if the scientific question was poorly framed.

In many scientific problems, there is no equivalent of:

```text
All tests passed.
```

The ground truth may require another experiment.

It may take weeks or months to obtain.

Sometimes the relevant evidence is incomplete, noisy, or impossible to observe directly.

This difference matters when we think about AI agents.

It is tempting to look at rapid progress in coding agents and assume that scientific agents will follow the same trajectory.

They probably will improve rapidly.

But success in coding should not automatically be extrapolated to scientific reasoning.

Coding has an unusually favorable feedback structure.

Science often does not.

As AI makes generation cheaper and faster, I suspect the bottleneck in scientific AI will increasingly shift away from generation itself.

The harder problem will be building reliable ways to determine whether the generated answer is actually correct.

**The bottleneck of scientific AI may be shifting from generation to verification.**
