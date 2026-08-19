---
title: "Math Test"
date: 2026-08-19
draft: false
tags:
  - mathematics
---

## Inline mathematics

Suppose \(X\) is a random variable with mean \(\mu\) and variance
\(\sigma^2\).

The probability of class \(y\) given input \(x\) is written as
\(p(y \mid x)\).

## Display mathematics

The arithmetic mean is

\[
\bar{x} =
\frac{1}{N}
\sum_{i=1}^{N}x_i.
\]

The cross-entropy loss is

\[
\mathcal{L}(\theta) =
-\frac{1}{N}
\sum_{i=1}^{N}
\sum_{c=1}^{C}
y_{ic}\log p_\theta(c \mid x_i).
\]

## Multiple aligned equations

\[
\begin{aligned}
z &= Wx + b \\
p &= \operatorname{softmax}(z) \\
\hat{y} &= \arg\max_c p_c
\end{aligned}
\]

