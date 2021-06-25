---
title: "Quantum circuit design methodology for multiple linear regression"
collection: publications
permalink: /publications/quantum_multiple_regression
excerpt: "**Authors**: Sanchayan Dutta, Adrien Suau, Sagnik Dutta, Suvadeep Roy, Bikash K Behera, Prasanta K Panigrahi"
date: 2020-10-09
venue: 'IET Quantum Communication'
# paperurl: 'https://digital-library.theiet.org/content/journals/10.1049/iet-qtc.2020.0013'
# citation:
---
<a href="https://arxiv.org/abs/1811.01726" class="btn btn-primary" target="_blank">arXiv</a>
<a href="https://doi.org/10.1049/iet-qtc.2020.0013" class="btn btn-primary" target="_blank">DOI</a>

**Abstract**: Multiple linear regression assumes an imperative role in supervised machine learning. In 2009, Harrow et al. [Phys. Rev. Lett. 103, 150502 (2009)] showed that their HHL algorithm can be used to sample the solution of a linear system Ax = b exponentially faster than any existing classical algorithm, with some manageable caveats. The entire field of quantum machine learning gained considerable traction after the discovery of this celebrated algorithm. However, effective practical applications and experimental implementations of HHL are still sparse in the literature. Here, we demonstrate a potential practical utility of HHL, in the context of regression analysis, using the remarkable fact that there exists a natural reduction of any multiple linear regression problem to an equivalent linear systems problem. We put forward a 7-qubit quantum circuit design, motivated from an earlier work by Cao et al. [Mol. Phys. 110, 1675 (2012)], to solve a 3-variable regression problem, using only elementary quantum gates. We also implement the Group Leaders Optimization Algorithm (GLOA) [Mol. Phys. 109 (5), 761 (2011)] and elaborate on the advantages of using such stochastic algorithms in creating low-cost circuit approximations for the Hamiltonian simulation. We believe that this application of GLOA and similar stochastic algorithms in circuit approximation will boost time- and cost-efficient circuit designing for various quantum machine learning protocols. Further, we discuss our Qiskit simulation and explore certain generalizations to the circuit design.
