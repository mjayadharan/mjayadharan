<h1 align="center">Hey 👋, I'm Manu</h1>

<p align="center">
  Applied mathematician and computational scientist<br>
  Postdoctoral Fellow, Engineering Sciences &amp; Applied Mathematics, Northwestern University
</p>

<p align="center">
  <a href="https://mjayadharan.github.io/"><img src="https://img.shields.io/badge/Website-mjayadharan.github.io-68f?style=for-the-badge" alt="Website"/></a>&nbsp;
  <a href="https://scholar.google.com/citations?user=s4yYujAAAAAJ&hl=en"><img src="https://img.shields.io/badge/Google%20Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white" alt="Google Scholar"/></a>&nbsp;
  <a href="https://www.linkedin.com/in/manu-jayadharan/"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>&nbsp;
  <a href="mailto:manu.jayadharan@gmail.com"><img src="https://img.shields.io/badge/Gmail-%23D14836.svg?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/></a>&nbsp;
  <a href="https://orcid.org/0009-0007-9287-3325"><img src="https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID"/></a>
</p>

---

I work at the intersection of **scientific machine learning, dynamical systems, and numerical methods**, with a focus on developing algorithms to discover real-world models. I design numerically stable, data-driven methods for discovering and solving differential equations and implement them as open-source software.

- 🔭 **Currently:** Postdoctoral Fellow at Northwestern University (with Dr. Niall Mangan), affiliated with the NSF–Simons National Institute for Theory and Mathematics in Biology (NITMB) and the Trienens Institute for Sustainability and Energy.
- 💼 **Previously:** Quantitative Analyst (AVP) at Citigroup, NYC (2021–2023), building large-scale C++ pricing and risk libraries for credit derivatives. PhD in Mathematics, University of Pittsburgh (2021).
- 📦 **Maintainer of** [`dae-finder`](https://pypi.org/project/dae-finder/), a model-agnostic Python package for discovering differential-algebraic equations from noisy data.
- 🤖 **New for Fall 2026:** teaching *Agentic AI for Scientific Computing*, a project-based graduate course at Northwestern on the principled, validated use of frontier AI agents (Claude Code, Codex/GPT, Gemini) in scientific computing.
- 🤝 Always open to new collaborators and interesting projects.

## What I work on

| | |
|---|---|
| **Equation discovery from data** | Stable, interpretable algorithms for learning differential-algebraic equations from noisy measurements: [SODAs](https://doi.org/10.1098/rspa.2025.0201) (*Proc. Royal Society A*, 2026), demonstrated on chemical reaction networks, the IEEE-39 power grid, and battery models. |
| **Inverse problems & ill-conditioning** | Why dictionary-based model discovery fails (diagnosed via inverse-problem theory) and how to fix it: QR-based library orthogonalization, multiple-shooting parameter estimation for stiff systems. |
| **Multiphysics PDE solvers** | Finite-element solvers for coupled Poisson–Nernst–Planck electrochemical systems; domain decomposition for Biot poroelasticity; MPI-parallel implementations. |
| **Agentic AI for scientific computing** | Protocols, validation frameworks, and reusable agentic skill sets so AI-assisted scientific computing is verifiable, reproducible, and accessible on lower-cost models. |

<p align="center">
  <a href="https://github.com/mjayadharan/BiotDD">
    <img src="https://user-images.githubusercontent.com/35903705/97790134-68adc980-1b9c-11eb-9431-ec5bfcc6da36.gif" alt="Poroelastic flow simulation computed with BiotDD" width="480">
  </a>
  <br>
  <em>Poroelastic flow simulated with my MPI-parallel solver <a href="https://github.com/mjayadharan/BiotDD">BiotDD</a></em>
</p>

## Featured projects

| Project | What it is | Stack |
|---|---|---|
| [**DAE-FINDER**](https://github.com/mjayadharan/DAE-FINDER_dev) ([PyPI](https://pypi.org/project/dae-finder/)) | Model-agnostic package for discovering differential-algebraic equations from data via sparse optimization; scikit-learn-compatible `.fit()`/`.score()` interface | Python |
| [**FluidLearn**](https://github.com/mjayadharan/FluidLearn) | Physics-informed neural networks for fluid-flow PDEs, packaged for domain scientists | Python, TensorFlow/Keras |
| [**MMMFE-ST-DD**](https://github.com/mjayadharan/MMMFE-ST-DD) | Parabolic-PDE solver using space-time multiscale mortar mixed finite elements with non-matching subdomain grids | C++, deal.II |
| [**BiotDD**](https://github.com/mjayadharan/BiotDD) | Poroelastic flow simulator using MPI-based non-overlapping domain decomposition | C++, MPI, deal.II |
| [**deal.II**](https://www.dealii.org/authors.html) | Contributor to the widely used open-source C++ finite element library | C++ |

## Selected publications

- **M. Jayadharan**, N. M. Mangan, et al., "SODAs: Sparse Optimization for Discovery of Differential-Algebraic Systems from Data," *Proc. Royal Society A*, 2026. [DOI](https://doi.org/10.1098/rspa.2025.0201)
- **M. Jayadharan**, I. Yotov, "Multiscale mortar mixed finite element methods for the Biot system of poroelasticity," *Comput. Methods Appl. Mech. Engrg.*, 2025.
- **M. Jayadharan**, M. Kern, M. Vohralík, I. Yotov, "A space-time multiscale mortar mixed finite element method for parabolic equations," *SIAM J. Numer. Anal.*, 2023.
- Y. Feng, N. M. Mangan, **M. Jayadharan**† (senior author), "Ill-conditioning in dictionary-based dynamic-equation learning," under review at *SIAM J. Life Sciences*, 2026.

Full list on [my website](https://mjayadharan.github.io/publications/) and [Google Scholar](https://scholar.google.com/citations?user=s4yYujAAAAAJ&hl=en).

## Toolbox

**Languages:** Python · C++ · Julia (previously MATLAB, Fortran)
**Scientific ML:** SINDy-family methods · neural ODEs · PINNs · sparse optimization
**Numerical methods:** FEM · domain decomposition · space-time methods · multiple shooting
**FEM / HPC:** deal.II · FEniCS · FreeFem++ · MPI · Slurm
**Data science:** NumPy · Pandas · SciPy · SymPy · scikit-learn · TensorFlow/Keras

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=mjayadharan&label=Profile+views" alt="Profile views">
</p>
