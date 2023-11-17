---
title: "Inferring Complexity Bounds from Recurrence Relations"
collection: talks
type: "Talk"
permalink: /talks/njpls
venue: "University of Pennsylvania"
date: 2023-5-19
location: "Philadelphia, PA"
---

This talk was given at the New Jersey Programming Languages and Systems Seminar (NJPLS), which brings researchers in the New Jersey area together for a day of informal talks and discussions. 

*Abstract*: Determining program complexity bounds is a fundamental problem with a variety of applications, such as performance debugging. We propose a novel approach for computing the asymptotic complexity bounds of non-deterministic recursive programs by solving dynamically inferred recurrence relations. Recurrences are inferred from program execution traces and solved using the annihilator method and Master Theorem to obtain closed-form solutions representing the complexity bounds. Our approach captures the worst-case execution behavior of programs using linear templates, enabling efficient inference of linear recurrences that express a wide-range of complexities, including non-linear polynomial and non-polynomial, logarithmic, and exponential bounds.
Our preliminary evaluation shows that this approach can learn correct bounds for popular classical recursive programs (e.g. 𝑛^2 for quicksort), achieving more precise complexity bounds for exponential programs than previously reported (e.g.𝑂(1.62^n)for Fibonacci). These dynamically inferred recurrences can also be applied to a more general user-defined resource bounds analysis such as bounding the number of API calls.
