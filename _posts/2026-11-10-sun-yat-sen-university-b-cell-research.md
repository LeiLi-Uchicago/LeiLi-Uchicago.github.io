---
layout: "post"
title: "Decoding B-cell Responses at Single-cell Resolution"
date: "2026-11-10 23:30:32 +0000"
categories: ["thoughts"]
tags: ["computational-biology", "single-cell", "scientific-ai"]
description: "What is the biological question, and what is the right computational way to answer it?"
linkedin: "https://www.linkedin.com/feed/update/urn:li:activity:7526063778820730880/"
---

It was a real pleasure to visit **Sun Yat-sen University** recently and give a talk as part of the 50th Anniversary Academic Lecture Series of the School of Public Health.

A special thanks to **Dr. Cheng Guo** for the invitation. Cheng and I worked in the same lab more than a decade ago, studying plant genes. Somehow, life took both of us into the very different—and very interesting—world of virology and immunology. This was also our first time meeting in person again in about 12 years.

So I used this talk as a chance to look back at my own research journey.

Over the past few years, much of my work has focused on **“Decoding B-cell Responses at Single-cell Resolution,”** mainly through three projects:

**Chimeric HA vaccination** (Guthmiller et al., Immunity, 2025) → **COVID-19** (Dugan et al., Immunity, 2021) → **Immune imprinting** (Sun et al., Nature, 2026)

The biological questions were very different, but the technical direction kept moving toward higher resolution of B-cell antigen recognition.

We started by connecting **cell state with BCR sequence**, asking which B cells drive durable and broadly reactive immunity. Then we added **antigen specificity**, allowing us to ask what each B cell actually recognizes. More recently, we extended this further by comparing recognition across related antigen variants, asking how previous immune history reshapes what B cells recognize.

Different biological questions, but one continuous technical path: **increasing the resolution at which we can connect B-cell state, BCR sequence, and antigen recognition.**

I also shared several computational tools I developed along the way—**Librator, VGenes, LinQ-View, HTOreader, RVEAtlas, and RSVrecon**. Most of them started in the same way: we had a biological or analytical problem, existing tools were not quite enough, so we built something to solve it.

And of course, I had to finish with **AI for Science**.

Instead of making a grand prediction about where AI is taking science, I shared some of my own recent experience with rapid prototyping, AI-assisted coding, benchmarking, and verification—and, most importantly, how a bioinformatician might “survive” the AI era. 😄

The tools have changed a lot over the years, and they are changing faster than ever.

But the question I keep coming back to is still very simple:

**What is the biological question, and what is the right computational way to answer it?**

It was great to discuss these ideas with students and junior faculty from both biology and bioinformatics backgrounds—and especially nice to reconnect with an old labmate after 12 years.

![Audience at the Sun Yat-sen University lecture]({{ '/img/thoughts/2026-11-10-sun-yat-sen-visit/lecture-1.jpg' | relative_url }})
