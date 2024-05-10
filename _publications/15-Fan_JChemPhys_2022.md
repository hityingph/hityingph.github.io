---
title: "15. Z. Fan, Y. Wang, P. Ying, K. Song, J. Wang, Y. Wang, Z. Zeng, K. Xu, E. Lindgren, J. M. Rahm, A. J. Gabourie, J. Liu, H. Dong, J. Wu, Y. Chen, Z. Zhong, J. Sun, P. Erhart, Y. Su, T. Ala-Nissila, GPUMD: A package for constructing accurate machine-learned potentials and performing highly efficient atomistic simulations. J Chem Phys 157, 114801 (2022)."
collection: publications
permalink: /publication/15-Fan_JChemPhys_2022
excerpt: 'We present our latest advancements of machine-learned potentials (MLPs) based on the neuroevolution potential (NEP) framework introduced in [Fan et al., Phys. Rev. B 104, 104309 (2021)] and their implementation in the open-source package GPUMD.We increase the accuracy of NEP models both by improving the radial functions in the atomic-environment descriptor using a linear combination of Chebyshev basis functions and by extending the angular descriptor with some four-body and five-body contributions as in the atomic cluster expansion approach.'
date: 2022-09-20
venue: 'The Journal of Chemical Physics'
---
![image](https://user-images.githubusercontent.com/54773018/216848036-076f8959-18fd-490c-8b0d-c4d22fca684a.png)

We present our latest advancements of machine-learned potentials (MLPs) based on the neuroevolution potential (NEP) framework introduced in Fan et al. [Phys. Rev. B 104, 104309 (2021)] and their implementation in the open-source package gpumd. We increase the accuracy of NEP models both by improving the radial functions in the atomic-environment descriptor using a linear combination of Chebyshev basis functions and by extending the angular descriptor with some four-body and five-body contributions as in the atomic cluster expansion approach. We also detail our efficient implementation of the NEP approach in graphics processing units as well as our workflow for the construction of NEP models and demonstrate their application in large-scale atomistic simulations. By comparing to state-of-the-art MLPs, we show that the NEP approach not only achieves above-average accuracy but also is far more computationally efficient. These results demonstrate that the gpumd package is a promising tool for solving challenging problems requiring highly accurate, large-scale atomistic simulations. To enable the construction of MLPs using a minimal training set, we propose an active-learning scheme based on the latent space of a pre-trained NEP model. Finally, we introduce three separate Python packages, viz., gpyumd, calorine, and pynep, that enable the integration of gpumd into Python workflows.

[Download paper here](http://hityingph.github.io/files/15-Fan_JChemPhys_2022.pdf)

[Related code and input files](https://gitlab.com/brucefan1983/nep-data)
