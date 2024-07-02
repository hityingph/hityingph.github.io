---
title: "X. Wu, W. Zhou, H. Dong, P. Ying, Y. Wang, B. Song, Z. Fan, S. Xiong, Correcting force error-induced underestimation of lattice thermal conductivity in machine learning molecular dynamics. The Journal of Chemical Physics 161, 014103 (2024)."
collection: publications
permalink: /publication/34-Wu_JChemPhys_2024
excerpt: 'We reveal that the fitting errors in the machine-learned forces against the reference ones are responsible for the underestimated LTC as they constitute external perturbations to the interatomic forces. Since the force errors of a NEP model and the random forces in the Langevin thermostat both follow a Gaussian distribution, we propose an approach to correcting the LTC by intentionally introducing different levels of force noises via the Langevin thermostat and then extrapolating to the limit of zero force error. '
date: 2024-07-01
venue: 'The Journal of Chemical Physics'
---
![image](https://github.com/hityingph/hityingph.github.io/assets/54773018/b846f687-edf6-49fd-8fc4-26e379309556)



Machine learned potentials (MLPs) have been widely employed in molecular dynamics simulations to study thermal transport. However, the literature results indicate that MLPs generally underestimate the lattice thermal conductivity (LTC) of typical solids. Here, we quantitatively analyze this underestimation in the context of the neuroevolution potential (NEP), which is a representative MLP that balances efficiency and accuracy. Taking crystalline silicon, gallium arsenide, graphene, and lead telluride as examples, we reveal that the fitting errors in the machine-learned forces against the reference ones are responsible for the underestimated LTC as they constitute external perturbations to the interatomic forces. Since the force errors of a NEP model and the random forces in the Langevin thermostat both follow a Gaussian distribution, we propose an approach to correcting the LTC by intentionally introducing different levels of force noises via the Langevin thermostat and then extrapolating to the limit of zero force error. Excellent agreement with experiments is obtained by using this correction for all the prototypical materials over a wide range of temperatures. Based on spectral analyses, we find that the LTC underestimation mainly arises from increased phonon scatterings in the low-frequency region caused by the random force errors.

[Download paper here](http://hityingph.github.io/files/34-Wu_JChemPhys_2024.pdf)

[Download SI here](https://doi.org/10.1063/5.0213811)

[Download reeference datasets and MLPs here](https://github.com/hityingph/supporting-info)
