---
layout: post
title: "Scientific AI Requires More Than Task Completion"
subtitle: "A technically correct workflow can still end with the wrong scientific interpretation."
date: 2026-09-03
categories:
  - thoughts
tags:
  - Scientific AI
  - Verification
  - AI Agents
  - Computational Biology
description: "Scientific AI should be evaluated not only by whether an agent completes a task, but by whether assumptions, interpretations, and reasoning remain defensible throughout the workflow."
linkedin: https://www.linkedin.com/posts/lei-li-46713b78_current-ai-benchmarks-often-focus-on-whether-activity-7501438934829182976-X4fI
---

Current AI benchmarks often focus on whether a model or agent can complete a task, use tools correctly, or continue working autonomously for long periods of time.

That makes sense for many engineering and everyday tasks. They are relatively high-tolerance: some intermediate steps can be imperfect, and even a slightly imperfect final output may still be useful.

Science is different.

In science, every critical step needs to be defensible. And even when the computation itself is technically correct, the final interpretation can still be wrong.

The assumptions may be wrong. A confounder may be missed. Association may be interpreted as causation. A transcriptional trajectory may be overinterpreted as developmental lineage.

These are not uniquely AI failures. Scientists have always made these mistakes.

The difference is **speed and scale**.

A scientific AI agent can now run an entire workflow:

> preprocessing → clustering → annotation → differential expression → pathway analysis → trajectory analysis → report

without ever crashing.

But suppose an early annotation is wrong.

Every downstream analysis may still execute perfectly. The code runs. The statistics are calculated. The figures look convincing. The report is coherent.

The entire workflow can therefore be locally correct while being globally wrong.

That creates an important distinction for scientific AI:

**Task completion is not the same as scientific reliability.**

High competence at individual steps does not automatically guarantee that the end-to-end reasoning remains sound.

For scientific AI, the evaluation questions therefore need to go beyond:

> Did the agent finish the task?

We should also ask:

- Did it check important assumptions?
- Did it notice anomalous results?
- Did it distinguish evidence from interpretation?
- Did it consider alternative explanations?
- Did it calibrate the strength of its claims?
- Did it know when the available evidence was insufficient?
- Could a scientist trace how the final conclusion was reached?

As AI systems become more capable, this type of verification may become increasingly important.

The goal is not to keep AI at arm's length. AI can be an extremely capable partner for technical implementation, cross-disciplinary reasoning, and scientific exploration.

But for scientific work, I think we should treat it as exactly that:

**a powerful thinking partner, not the final authority.**
