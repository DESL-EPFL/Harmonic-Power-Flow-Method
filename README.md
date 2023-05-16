# Harmonic Power-Flow Study

[![DOI](https://zenodo.org/badge/599111648.svg)](https://zenodo.org/badge/latestdoi/599111648)

This repository comprehends a Matlab project for the Harmonic Power-Flow (HPF) calculus in power systems with a high share of Converter-Interfaced Distributed Energy Resources (CIDERs). The project consists of:

* The Matlab Code performing the HPF study proposed in [[1]](#1), [[2]](#2) and its extensions as in [[3]](#3), [[4]](#4).
* The Simulink models for its validation.
* A [report](https://github.com/DESL-EPFL/HPF/files/10707231/Report.pdf) including detailed explanations of the project.

The HPF framework is capable of analyzing systems in periodic steady-state. It considers the propagation of the fundamental and harmonic frequencies and, specifically, includes the coupling between them. The Simulink models are used to perform Time-Domain Simulations (TDS), that are transformed to frequency domain spectra by means of the Fourier analysis. 
Multiple examples are provided, including the validation of the individual resource models of different types of CIDERs as well as entire distribution grids based on benchmark systems from CIGRÉ. The code and framework are designed in a generic way, such that the inclusion and analysis of additional types of CIDERs and/or other configurations of power systems is straightforward.

## Software

The following software is required to run the code:
* MATLAB Version R2021b
* Simulink Version R2021b


## References
<a id="1">[1]</a>
A. M. Kettner, L. Reyes-Chamorro, J. K. M. Becker, Z. Zou, M. Liserre, and M. Paolone, “Harmonic power-flow study of polyphase grids with converter-interfaced distributed energy resources—part i: Modeling framework and algorithm,” IEEE Trans. Smart Grid, vol. 13, no. 1, pp. 458–469, 2021.

<a id="2">[2]</a>
J. K. M. Becker, A. M. Kettner, L. Reyes-Chamorro, Z. Zou, M. Liserre, and M. Paolone, “Harmonic power-flow study of polyphase grids with converter-interfaced distributed energy resources—part ii: Model library and validation,” IEEE Trans. Smart Grid, vol. 13, no. 1, pp. 470–481, 2021.

<a id="3">[3]</a>
J. K. M. Becker, A. M. Kettner, Y. Zuo, et al., “Modelling of ac/dc interactions of converter-interfaced resources for harmonic power-flow studies in microgrids,” IEEE Trans. Smart Grid, 2022.

<a id="4">[4]</a>
J. K. M. Becker, A. M. Kettner, Y. Zuo, and M. Paolone, “Harmonic power-flow study of hybrid ac/dc grids with converter-interfaced distributed energy resources,” arXiv, 2023. doi: 10.48550/ARXIV.2302.02864. [Online]. Available: https://arxiv.org/abs/2302.02864.
