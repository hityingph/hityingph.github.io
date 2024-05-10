---
title: "24. P. Ying, T. Liang, K. Xu, J. Zhang, J. Xu, Z. Zhong, Z. Fan, Sub-Micrometer Phonon Mean Free Paths in Metal-Organic Frameworks Revealed by Machine Learning Molecular Dynamics Simulations. ACS Appl Mater Interfaces 15, 36412-36422 (2023)."
collection: publications
permalink: /publication/24-Ying_ACSApplMaterInterfaces_2023
excerpt: 'We develop a set of accurate yet highly efficient machine-learned potentials for three typical MOFs and perform extensive MD simulations to study thermal transport in the three MOFs. We found the phonon mean free paths (MFPs) of MOFs can reach the sub-micrometer scale in the low-frequency region. The sub-micrometer phonon MFPs are also found to be correlated with a moderate temperature dependence of thermal conductivity between those in typical crystalline and amorphous materials.'
date: 2023-08-03
venue: 'ACS Applied Materials & Interfaces'
---
![image](https://github.com/hityingph/hityingph.github.io/assets/54773018/46007af1-6829-47aa-a4f0-bf01fa14df6f)

Metal–organic frameworks (MOFs) are a family of materials that have high porosity and structural tunability and hold great potential in various applications, many of which require a proper understanding of the thermal transport properties. Molecular dynamics (MD) simulations play an important role in characterizing the thermal transport properties of various materials. However, due to the complexity of the structures, it is difficult to construct accurate empirical interatomic potentials for reliable MD simulations of MOFs. To this end, we develop a set of accurate yet highly efficient machine-learned potentials for three typical MOFs, including MOF-5, HKUST-1, and ZIF-8, using the neuroevolution potential approach as implemented in the GPUMD package, and perform extensive MD simulations to study thermal transport in the three MOFs. Although the lattice thermal conductivity values of the three MOFs are all predicted to be smaller than 1 W/(m K) at room temperature, the phonon mean free paths (MFPs) are found to reach the sub-micrometer scale in the low-frequency region. As a consequence, the apparent thermal conductivity only converges to the diffusive limit for micrometer single crystals, which means that the thermal conductivity is heavily reduced in nanocrystalline MOFs. The sub-micrometer phonon MFPs are also found to be correlated with a moderate temperature dependence of thermal conductivity between those in typical crystalline and amorphous materials. Both the large phonon MFPs and the moderate temperature dependence of thermal conductivity fundamentally change our understanding of thermal transport in MOFs.

[Download paper here](http://hityingph.github.io/files/24-Ying_ACSApplMaterInterfaces_2023.pdf)

[Download support materials here](https://pubs.acs.org/doi/suppl/10.1021/acsami.3c07770/suppl_file/am3c07770_si_001.pdf)

[Training datasets for the NEP model](https://gitlab.com/brucefan1983/nep-data/)

[Representive input files](https://github.com/hityingph/supporting-info/tree/main/24-Ying_ACSApplMaterInterfaces_2023)
