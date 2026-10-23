---
title: "Core flow inversion benchmark"
layout: "simple"
date: 2026-10-23
---

We propose a benchmarking exercise for the recovery of core surface flows from the knowledge of the main magnetic field and its rate of change (or secular variation) at the core-mantle boundary. 
This exercise is based on synthetic data generated from numerical simulations of the geodynamo, as well as geomagnetic data. 
We distinguish between three configurations:
1. Recovery of a simulated static flow field at a given snapshot in time.
2. Recovery of simulated transient flows from time-dependent magnetic variations.
3. Inversion of core flows from geomagnetic data, for which an intercomparison of the candidate solutions will be proposed.

The **submission** of candidate flow models is open **until end of April 2027**, on this Gitlab repository:

[https://gitlab.com/4d-earth-core/core-flow-inversion-benchmark](https://gitlab.com/4d-earth-core/core-flow-inversion-benchmark).

## About the benchmark exercise

Please see the details on the [Gitlab repository](https://gitlab.com/4d-earth-core/core-flow-inversion-benchmark) and the [notes on the benchmark exercise](https://gitlab.com/4d-earth-core/core-flow-inversion-benchmark/-/blob/0e4c10be3ee117c341e29acd23988a57b15f46ea/benchmark-exercise.pdf).

## Overview of the process
{{< mermaid >}}
timeline
    section Upload input data
        Available by October 2026 : Reference MF & SV coeff. (train & blind) : Reference CF coeff. (train)

    section Production of candidate model(s)

    section Upload candidate model(s)
        By end of April, 2027 : Inverted coeff. (train & blind) : Technical note

    section Evaluation of candidates
        By end of September, 2027 : Quantitative and qualitative intercomparison led by 4D-Earth-Core+ consortium : Collective publication involving all candidate teams
{{< /mermaid >}}

