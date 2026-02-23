---
permalink: /software/
author_profile: false
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

## Arvert

Inverts 40Ar/39Ar age spectra and associated mineral ages for thermal history using the Controlled Random Search (CRS) algorithm.

- **Software**: <https://github.com/OpenThermochronology/Arvert>
- **Documentation**: <https://github.com/OpenThermochronology/Arvert/blob/main/Arvert%207.01%20manual.pdf>
- **License**: GNU General Public License v3.0
- **Programming language**: C++
- **Citable(s)**: None

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

## diffsim

Random-walk simulation of He diffusion in minerals with trapping into reversible sinks.

- **Software**: <https://github.com/OpenThermochronology/diffsim>
- **Documentation**: <https://github.com/OpenThermochronology/diffsim/blob/main/README.md>, <https://github.com/OpenThermochronology/diffsim/blob/main/diffsim_background.pdf>
- **License**: GNU General Public License v3.0
- **Programming language**: C++
- **Citable(s)**: None

## Domains

Inversion code to determine diffusion-domain structure of a multi diffusion domain sample (usually K-feldspar).

- **Software**: <https://github.com/OpenThermochronology/domains>
- **Documentation**: <https://github.com/OpenThermochronology/domains/blob/main/domains_manual.md>
- **License**: GNU General Public License v3.0
- **Programming language**: Fortran
- **Citable(s)**: None

## EmpiricalBayes

Uses of a form of Empirical Bayes resampling (also known as Hierarchical Bayes) for more robust (U-Th)/He data uncertainty estimation for use in time-temperature history inversions.

- **Software**: <https://github.com/OpenThermochronology/EmpiricalBayes>
- **Documentation**: <https://github.com/OpenThermochronology/EmpiricalBayes/blob/main/README.md>
- **License**: GNU General Public License v3.0
- **Programming language**: Julia
- **Citable(s)**: None

## eUage

Runs a loop across a range of effective uranium values for sample data and an input thermal history to calculate predicted date-eU relationships using the RDAAM of Flowers et al. 2009 or ZRDAAM of Guenthner et al. 2013.

- **Software**: <https://github.com/OpenThermochronology/eUage>
- **Documentation**: <https://github.com/OpenThermochronology/eUage/blob/main/README.md>
- **License**: GNU General Public License v3.0
- **Programming language**: C++
- **Citable(s)**: None

## ftee

Calculates alpha-loss correction factor for U-Th/He dating.

- **Software**: <https://github.com/OpenThermochronology/ftee>
- **Documentation**: <https://github.com/OpenThermochronology/ftee/blob/main/ftee113%20manual.pdf>
- **License**: GNU General Public License v3.0
- **Programming language**: C
- **Citable(s)**: None

## JuliaThermoTools

Thermochronology codes for data handling, plotting, and simple calculations.

- **Software**: <https://github.com/OpenThermochronology/JuliaThermoTools/>
- **Documentation**: None
- **License**: GNU General Public License v3.0
- **Programming language**: Julia
- **Citable(s)**: None

## kfcorr

Calculates cross-correlations between age spectra and their associated logRRo plot.

- **Software**: <https://github.com/OpenThermochronology/kfcorr>
- **Documentation**: <https://github.com/OpenThermochronology/kfcorr/blob/main/README.md>
- **License**: GNU General Public License v3.0
- **Programming language**: Fortran 90
- **Citable(s)**: None

## Pecube

Pecube is a 3D thermo-kinematic model for forward and inverse modeling of thermochronological data.

- **Software**: <https://github.com/jeanbraun/Pecube>
- **Documentation**: <https://github.com/jeanbraun/Pecube/blob/master/docs/Pecube.pdf>
- **License**: GNU General Public License v3.0
- **Programming language**: Fortran (mostly)
- **Citable(s)**: <https://doi.org/10.1016/S0098-3004(03)00052-9>, <https://doi.org/10.1016/j.tecto.2011.12.035>

## Pecube-HUGG

The Helsinki University Geodynamics Group (HUGG) version of Pecube. Modified from the version of Braun et al. (2012).

- **Software**: <https://github.com/HUGG/Pecube-HUGG>
- **Documentation**: <https://github.com/HUGG/Pecube-HUGG/blob/master/README.md>
- **License**: None listed
- **Programming language**: Fortran (mostly)
- **Citable(s)**: <https://doi.org/10.1016/j.tecto.2011.12.035>

## PyThermo

A Python package for forward modeling of apatite and zircon (U-Th)/He data using various diffusion and damage annealing kinetic models.

- **Software**: <https://github.com/OpenThermochronology/PyThermo>
- **Documentation**: <https://github.com/OpenThermochronology/PyThermo/blob/main/README.md>
- **License**: GNU General Public License v3.0
- **Programming language**: Python
- **Citable(s)**: <https://doi.org/10.17605/OSF.IO/BNUVZ>

## QTQtPlot

Takes the raw time-temperature (t-T) output file from the QTQt thermal history modelling software of Gallagher (2012) and replots the output as an image displaying t-T path density.

- **Software**: <https://github.com/OpenThermochronology/QTQtPlot>
- **Documentation**: <https://github.com/OpenThermochronology/QTQtPlot/blob/main/README.md>
- **License**: GNU General Public License v3.0
- **Programming language**: Julia
- **Citable(s)**: None

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

## Helsinki University Geodynamics Group (HUGG)

HUGG maintains GitHub repositories for various software packages, including those intended for use with thermochronological data, in their GitHub organization. Several packages listed above can be found there, in addition to other software.

- **Repository**: <https://github.com/HUGG>

## Open Thermochronology on GitHub

Open Thermochronology maintains a GitHub organization for open-source thermochronology software. Many of the software packages mentioned above can be accessed from the link below. If you are interested in hosting your software in the Open Thermochronology GitHub organizations, let us know.

- **Repository**: <https://github.com/OpenThermochronology>