---
title: One paper titled “Compiler-Guided Polynomial-Level Parallelism for FHE-Encrypted Machine Learning Inference” has been accepted by HLPP 2026. Congratulations to Zijian Duan.
date: 2026-06-03
image:
  focal_point: 'top'
authors:
  - duanzijian
---

[HLPP 2026](https://sites.google.com/view/hlpp-2026) has accepted this work on compiler-guided optimization for fully homomorphic encryption (FHE)-encrypted machine learning inference. Congratulations to Zijian Duan.

The paper introduces CRISP, a compiler-reasoned inter-stage safe parallelization approach that exposes polynomial-level parallelism during compilation. Instead of relying only on hard-coded FHE libraries or runtime SIMD vectorization, CRISP applies compile-time OpenMP parallelism while preserving data dependences and cryptographic invariants across lowering and transformation stages.

Implemented in ANT-ACE, CRISP also coordinates polynomial-level parallelization with fusion optimizations. The evaluation on an Intel multi-core CPU platform shows a 2.65x mean speedup on polynomial-level operations, a 5.63% mean execution-time reduction on ML operators, and an average 137-second reduction in end-to-end ML inference latency.
