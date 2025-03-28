preCICE is an **open-source coupling library** for partitioned multi-physics simulations, including, but not restricted to fluid-structure interaction and conjugate heat transfer simulations.

Partitioned means that **preCICE couples existing programs/solvers** capable of simulating a subpart of the complete physics involved in a simulation. This allows for the high flexibility that is needed to keep a decent time-to-solution for complex multi-physics scenarios.

The software offers convenient methods for transient equation coupling, communication, and data mapping. Read more on the [preCICE website](https://precice.org/), or join our upcomig workshop:

![precice2025-slide-photo](https://github.com/user-attachments/assets/33b44c20-01c1-4a34-8e7b-040a03107667)

preCICE consists of several components, most of which are released as part of the [preCICE Distribution](https://precice.org/installation-distribution.html):
- The [core library](https://github.com/precice/precice) (in C++, with bindings in C and Fortran)
- Language bindings for [Python](https://github.com/precice/python-bindings), [Julia](https://github.com/precice/PreCICE.jl), [Matlab](https://github.com/precice/matlab-bindings), [Rust](https://github.com/precice/rust-bindings), as well as a [Fortran module](https://github.com/precice/fortran-module)
- Ready-to-use adapters for several open-source codes, including [OpenFOAM](https://github.com/precice/openfoam-adapter), [CalculiX](https://github.com/precice/calculix-adapter), [deal.II](https://github.com/precice/dealii-adapter), [FEniCS legacy](https://github.com/precice/fenics-adapter), [FEniCS-X](https://github.com/precice/fenicsx-adapter), [DUNE](https://github.com/precice/dune-adapter), [DuMuX](https://github.com/precice/dumux-adapter), [SU2](https://github.com/precice/su2-adapter), [MBDyn](https://github.com/precice/mbdyn-adapter), [code_aster](https://github.com/precice/code_aster-adapter), and [more](https://precice.org/adapters-overview.html).
- [Tutorials](https://github.com/precice/tutorials) with case files for several applications, solvers, and preCICE features.
- A [Vagrant box](https://github.com/precice/vm), which serves as a demo virtual machine with preCICE and several solvers already installed.
- The [preCICE website and documentation](https://github.com/precice/precice.github.io)

When using or referring to preCICE in academic publications, please follow the [citation guidelines](https://precice.org/fundamentals-literature-guide.html). More specifically, cite the preCICE v2 reference paper and any reference papers of adapters you may be using. For reproduibility, you may also want to use components from a preCICE distribution version and cite the respective [data repository entry](https://darus.uni-stuttgart.de/dataverse/ipvs_us3).

```bibtex
@article{preCICEv2,
  author = {Chourdakis, G and Davis, K and Rodenberg, B and Schulte, M and Simonis, F and Uekermann, B and Abrams, G and Bungartz, HJ and Cheung Yau, L and Desai, I and Eder, K and Hertrich, R and Lindner, F and Rusch, A and Sashko, D and Schneider, D and Totounferoush, A and Volland, D and Vollmer, P and Koseomur, OZ},
  title = {{preCICE} v2: A sustainable and user-friendly coupling library [version 2; peer review: 2 approved]
  },
  journal = {Open Research Europe},
  volume = {2},
  year = {2022},
  number = {51},
  doi = {10.12688/openreseurope.14445.2},
  url = {https://doi.org/10.12688/openreseurope.14445.2}
}
```
