---
layout: post
title: "Verification Is Becoming the Bottleneck in Scientific AI"
subtitle: "Generation scales faster than expert review."
date: 2026-09-27
categories:
  - thoughts
tags:
  - Scientific AI
  - AI Agents
  - Human Oversight
  - Verification
description: "As AI accelerates scientific generation, human verification can become the limiting step. The challenge is not only keeping humans in the loop, but deciding where human judgment must remain essential."
linkedin: https://www.linkedin.com/posts/lei-li-46713b78_very-interesting-perspective-i-think-there-activity-7509688773455245312-R0Gj
---

One concern I keep coming back to is that AI generation scales much faster than human verification.

An agent can now compress hours of work into minutes.

It can read papers, write code, run analyses, generate figures, summarize results, and draft interpretations in a single workflow.

That is extremely useful.

But the verification cost does not necessarily shrink at the same rate.

A scientist still needs to inspect assumptions, check biological plausibility, review intermediate results, and decide whether the final claim is justified.

In some domains, verification is cheap.

If a program fails a unit test, the problem is visible immediately.

In science, the verifier is often another scientist.

And expert attention is expensive.

This creates a scaling problem.

Suppose an AI agent can produce ten times more analyses in the same amount of time.

Can a human meaningfully review ten times more scientific reasoning?

Probably not.

At some point, "human in the loop" can become a weak safeguard if the human is simply approving work faster than they can genuinely evaluate it.

The problem is therefore not only:

> How do we keep humans in the loop?

A more important question may be:

> Where must human judgment remain essential?

This distinction matters because not every step requires the same level of oversight.

Some tasks can probably be delegated almost completely:

- repetitive preprocessing,
- standardized QC,
- code generation,
- report formatting,
- routine data transformation.

Other steps are much harder to delegate safely:

- deciding whether an assumption is biologically reasonable,
- recognizing an unexpected pattern,
- judging whether a result is plausible,
- distinguishing correlation from mechanism,
- deciding what evidence would change the conclusion.

The challenge is not to insert a human everywhere.

It is to identify the points where human judgment has the highest value.

This may also mean that scientific AI needs better machine-verifiable checks, rather than relying entirely on expert review.

If we can convert some scientific failure modes into explicit checks, we can reduce the verification burden.

But many important scientific judgments are still difficult to formalize.

That is why I think verification will become one of the central design problems for scientific AI.

AI is making generation dramatically cheaper.

The next question is whether we can make **trustworthy verification** scale with it.
