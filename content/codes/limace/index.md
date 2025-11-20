---
title: "Limace.jl"
summary: "Solve for linear eigenmodes of the rotating magnetohydrodynamics equations in a sphere."
date: 2025-09-30
draft: false
---

![Malkus modes](malkus_modes_limacejl.png "Malkus mode computed Limace.jl following [the example in the documentation](https://fgerick.github.io/Limace.jl/dev/examples/malkusmodes/).")

Hydromagnetic modes in spherical domains are an important ingredient of liquid cores of planets, moons or stars, as well as rotating fluid dynamics experiments. These modes are solutions to the linearized rotating magnetohydrodynamic equations that govern electrically conducting fluids under rapid rotation. _Limace.jl_ is a package written in the Julia programming language, based on Galerkin projections of the governing equations onto trial vectors of the velocity and magnetic field. It aims to facilitate the calculation of modes in flexible setups with a high-level interface, whilst remaining computationally performant enough to tackle relevant physical parameters. See [Gerick (2025)](https://fgerick.github.io/4dearth/publications/#2025) and [Gerick & Livermore (2024)](https://fgerick.github.io/4dearth/publications/#2024) for more details on the model.



The code is available on [GitHub](https://github.com/fgerick/Limace.jl).


Contact: Felix Gerick