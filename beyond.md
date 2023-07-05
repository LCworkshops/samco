---
layout: default
permalink: /beyond/
nav_order: 7
title: SAMCO - Beyond one model per objective
---



# Subgroup "Beyond one model per objective function"  #
---


Assumptions

1. dimensions can not be reduced
2. initially no coorelation bw obj functions

Problems - Point 1: model per objective function a) without correlation b) with correlation c) Multi-fidelity --> quality and cost

f: R - R&d - problem with training data - multivariate Gaussian process - coKriging - You need training data to build right correlation

1. g_1,…g_d: R x R ^ d- i → R → wrong
2. same fiedility for all m1,…md
3. different fiedilties - general
4. g_1, g_d R → R - Traditional way of doing it, combining these two models we have not defined yet
5. Multiple objectives of same fiediltiy →
State-of-the-art = approximate each

1. Solutions - multivariabte Gaussian process for coorelation functions


Issues

1. Scalability
2. Traianing time
3. Correlation - losing the information
4. infill criteria
5. Size and distrbution of traianing data
6. Convergence and diversity


Solutions -

1. - multivariate Gaussian process, example: Quality and cost

Point 2: n models for 1 objective function Solutions - Different traianing data for different models - robustness

Point 3: Combining many models