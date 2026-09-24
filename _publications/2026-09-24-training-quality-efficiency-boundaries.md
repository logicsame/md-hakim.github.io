---
title: "Training Quality Determines Efficiency Boundaries in Test-Time Reasoning"
collection: publications
category: preprints
permalink: /publication/2026-training-quality-efficiency-boundaries
excerpt: 'This paper establishes training quality as the primary determinant of reasoning efficiency in large language models, evaluating 50 models across 67,000+ assessments to show when additional inference tokens help, are redundant, or actively harm accuracy.'
date: 2026-09-24
venue: 'NeurIPS 2026 (Accepted Poster)'
paperurl: 'https://arxiv.org/abs/XXXX.XXXXX'
citation: 'Hakim, MD Azizul. (2026). &quot;Training Quality Determines Efficiency Boundaries in Test-Time Reasoning.&quot; <i>Neural Information Processing Systems (NeurIPS 2026, Accepted Poster)</i>.'
---

This paper establishes that training quality is the primary determinant of reasoning efficiency in large language models, yielding greater returns than proportional increases in inference computation. Evaluating 50 language models (0.5B–685B parameters) across six reasoning benchmarks totalling over 67,000 assessments, the study identifies when additional inference tokens are beneficial, redundant, or actively harmful.

Standard models exhibit near-universal accuracy convergence at approximately 1,000 tokens regardless of architecture, parameter count, or decoding strategy. Causal intervention experiments demonstrate that constraining generation length improves reasoning accuracy by 15.4 percentage points, identifying over-generation — rather than capacity exhaustion — as the primary efficiency bottleneck. Among 19 reasoning-specialised models, training methodology yields a 5.0–18.8-fold efficiency gap at matched parameter scales, a gap that widens with generation budget and exceeds gains from ten-fold parameter increases.

Graduate-level evaluation reveals that arithmetic benchmark performance does not predict reasoning capability on complex tasks (r = −0.027, P = 0.915, n = 18), exposing fundamental limitations invisible to standard evaluation practice. Mechanistic profiling reveals two orthogonal dimensions of training quality — quality control and decomposition efficiency — that independently predict efficiency profiles, providing a measurable framework linking training decisions to inference-time behaviour.

**Authors:**

*   **MD Azizul Hakim** (Sole Author, Independent Researcher, Bangladesh Sweden Polytechnic Institute, Bangladesh)

**Venue:** Neural Information Processing Systems (NeurIPS 2026) — Accepted Poster

**Year:** 2026

**arXiv:** [XXXX.XXXXX](https://arxiv.org/abs/XXXX.XXXXX)

**Keywords:** Large language models, test-time reasoning, inference efficiency, training quality, reasoning-specialised models, mechanistic evaluation