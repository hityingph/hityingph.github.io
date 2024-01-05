---
title: "Ying, P.; Fan, Z. Combining the D3 dispersion correction with the neuroevolution machine-learned potential. Journal of Physics: Condensed Matter 2023, 36 (12). DOI: 10.1088/1361-648X/ad1278"
collection: publications
permalink: /publication/28-Ying_JPhysCondensMatter_2024
excerpt: 'We propose to combine the neuroevolution potential (NEP) with the popular D3 correction to achieve a unified NEP-D3 model that can simultaneously model relatively short-ranged bonded interactions and relatively long-ranged dispersion interactions.'
date: 2023-12-14
venue: 'Journal of Physics: Condensed Matter'
---
<img width="600" alt="image" src="https://github.com/hityingph/hityingph.github.io/assets/54773018/2d328c6e-8129-4c97-b63f-d7318ea42445">

Machine-learned potentials (MLPs) have become a popular approach of modeling interatomic interactions in atomistic simulations, but to keep the computational cost under control, a relatively short cutoff must be imposed, which put serious restrictions on the capability of the MLPs for modeling relatively long-ranged dispersion interactions. In this paper, we propose to combine the neuroevolution potential (NEP) with the popular D3 correction to achieve a unified NEP-D3 model that can simultaneously model relatively short-ranged bonded interactions and relatively long-ranged dispersion interactions. We show that improved descriptions of the binding and sliding energies in bilayer graphene can be obtained by the NEP-D3 approach compared to the pure NEP approach. We implement the D3 part into the gpumd package such that it can be used out of the box for many exchange-correlation functionals. As a realistic application, we show that dispersion interactions result in approximately a 10% reduction in thermal conductivity for three typical metal-organic frameworks.

[Download paper here](http://hityingph.github.io/files/28-Ying_JPhysCondensMatter_2024.pdf)


[Training datasets for the NEP model](https://gitlab.com/brucefan1983/nep-data)

