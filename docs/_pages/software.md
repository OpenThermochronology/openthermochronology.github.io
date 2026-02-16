---
permalink: /software/
author_profile: true
layout: single
title: "Software and online repositories"
toc: true
toc_label: "Software links"
toc_icon: "computer"  # corresponding Font Awesome icon name (without fa prefix)
---

The sections below provide short descriptions and links to various open-source thermochronology software packages and/or online software repositories. In each case, there are links to the software itself, documentation (if available), and references that should be cited when using the software.

# Software

<!--
## Template for a software listing

<img src="{{ site.url }}{{ site.baseurl }}/assets/images/image.png" alt="Image alt text" width="500">

Short summary sentence or two.

- **Software**: <url to access source code>
- **Documentation**: <documentation url>
- **License**: License type
- **Programming language**: List relevant language(s)
- **Citable(s)**: <DOIs or other identifiers>, <...>
-->

## CoolingFDHM

Estimates the timing of initial cooling in a QTQt time-temperature inversion by the full duration at half-maximum (FDHM) method.

- **Software**: <https://github.com/OpenThermochronology/CoolingFDHM>
- **Documentation**: None
- **License**: GNU General Public License v3.0
- **Programming language**: Julia
- **Citable(s)**: <https://doi.org/10.5194/gchron-2024-3>

## Detrital MC

<img src="{{ site.url }}{{ site.baseurl }}/assets/images/detrital-mc.png" alt="Example Detrital MC plot" width="500">

Program for plotting and comparing measured and predicted detrital age distributions as PDFs, CDFs or ECDFs. Monte Carlo sampling of predicted ages can be performed as well. 

- **Software**: <https://github.com/HUGG/Detrital-MC>
- **Documentation**: <https://detrital-mc.readthedocs.io/>
- **License**: GNU General Public License v3.0
- **Programming language**: Fortran
- **Citable(s)**: <https://doi.org/10.5281/zenodo.15264992>

## Domains

Inversion code to determine diffusion-domain structure of a multi diffusion domain sample (usually K-feldspar).

- **Software**: <https://github.com/OpenThermochronology/domains>
- **Documentation**: <https://github.com/OpenThermochronology/domains/blob/main/domains_manual.md>
- **License**: GNU General Public License v3.0
- **Programming language**: Fortran
- **Citable(s)**: None

## JuliaThermoTools

Thermochronology codes for data handling, plotting, and simple calculations.

- **Software**: <https://github.com/OpenThermochronology/JuliaThermoTools/tree/main>
- **Documentation**: None
- **License**: GNU General Public License v3.0
- **Programming language**: Julia
- **Citable(s)**: None

## Pecube

Pecube is a 3D thermo-kinematic model for forward and inverse modeling of thermochronological data.

- **Software**: <https://github.com/jeanbraun/Pecube>
- **Documentation**: <https://github.com/jeanbraun/Pecube/blob/master/docs/Pecube.pdf>
- **License**: GNU General Public License v3.0
- **Programming language**: Fortran (mostly)
- **Citable(s)**: <https://doi.org/10.1016/S0098-3004(03)00052-9>, <https://doi.org/10.1016/j.tecto.2011.12.035>

## PyThermo

A Python package for forward modeling of apatite and zircon (U-Th)/He data using various diffusion and damage annealing kinetic models.

- **Software**: <[url to access source code](https://github.com/OpenThermochronology/PyThermo)>
- **Documentation**: <[documentation url](https://github.com/OpenThermochronology/PyThermo/blob/main/README.md)>
- **License**: GNU General Public License v3.0
- **Programming language**: Python
- **Citable(s)**: <https://doi.org/10.17605/OSF.IO/BNUVZ>

## T<sub>c</sub>plotter

<img src="{{ site.url }}{{ site.baseurl }}/assets/images/tcplotter.png" alt="Example Tcplotter plot" width="500">

Create plots of predicted thermochronometer ages and closure temperatures for various cooling histories and mineral parameters.

- **Software**: <https://github.com/HUGG/tcplotter>
- **Documentation**: <https://tcplotter.readthedocs.io/>
- **License**: MIT License
- **Programming language**: Python (mostly)
- **Citable(s)**: <https://doi.org/10.5281/zenodo.5958939>, <https://doi.org/10.5194/gchron-4-143-2022>

## T<sub>c</sub>1D

<img src="{{ site.url }}{{ site.baseurl }}/assets/images/tc1d.png" alt="Example Tc1D plot" width="500">

T<sub>c</sub>1D is a one-dimensional thermal and thermochronometer age prediction model that can simulate the effects of various geodynamic and geomorphic processes on thermochronometer ages. It supports both forward and inverse modeling of thermochronometer data.

- **Software**: <https://github.com/HUGG/TC1D>
- **Documentation**: <https://tc1d.readthedocs.io/>
- **License**: GNU General Public License v3.0
- **Programming language**: Python (mostly)
- **Citable(s)**: <https://doi.org/10.5281/zenodo.7124271>

## Thermochron.jl

Thermochron.jl is open-source software for time-temperature inversion of thermochronometric data. It implements a transdimensional Bayesian Markov chain Monte Carlo (MCMC) time-Temperature inversion with optional Simulated Annealing and kinetic uncertainty propagation/inversion.

- **Software**: <https://github.com/OpenThermochronology/Thermochron.jl>
- **Documentation**: <https://openthermochronology.github.io/Thermochron.jl/dev/>
- **License**: GNU General Public License v3.0
- **Programming language**: Julia
- **Citable(s)**: <https://doi.org/10.17605/osf.io/wq2U5>

# Software repositories

## Open Thermochronology on GitHub

Open Thermochronology maintains a GitHub organization for open-source thermochronology software. Many of the software packages mentioned above can be accessed from the link below. If you are interested in hosting your software in the Open Thermochronology GitHub organizations, let us know.

- **Repository**: <https://github.com/OpenThermochronology>