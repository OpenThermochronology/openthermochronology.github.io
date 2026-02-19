---
permalink: /about/
author_profile: true
layout: single
classes: wide
---

The Open Thermochronology initiative is an effort to support open, reproducible science by sharing and developing community tools for numerical modeling and data processing/visualization.

# Motivation

The present scientific landscape is embracing open science as a means to ensure research results are broadly accessible (including datasets, software, methodologies, peer review, etc.) and to expand the dissemination and production of science. Software is a key piece in the open science world, as it is used both to produce results and train new researchers. For example, the availability of open-source software is seen as increasingly valuable by publishers to ensure results can be replicated (see AGU’s publishing [policies](https://www.agu.org/publications/authors/journals/data-software-for-authors) for data and software, for example). In our thermochronology community, there are presently several well-established, widely used software packages for modeling and interpreting thermochronometer data (e.g., HeFTy, Pecube, QTQt, etc.). These software packages have been instrumental in pushing thermochronology in a computational direction, and provide a solid foundation upon which to build further data analysis and modeling tools. While these packages have and continue to serve our community well, there is no open-source toolkit designed for thermochronology users that want to reduce, interpret, or graphically present data in ways that are not restricted to the specific output of these  inverse thermal history modeling packages. Our community also lacks a common open-source library of tools available to users to utilize in their software and workflows, or for developers to easily share new functions/visualization tools with the wider community.

A lack of easy-to-use open-source modeling tools has led users in the community to write (and rewrite) their own codes in an *ad hoc* fashion to model, interpret, and visualize thermochronometer data. In addition, although mature software packages are helpful for scientific use, their use for teaching may be more limited as students are unable to get a look "under the hood" to see the details of how they operate. Furthermore, software developed in the broader community can provide an opportunity for researchers to get involved and co-develop tools to best serve our collective needs.
 
Initial efforts towards ameliorating these issues exist in the form of a GitHub organization, [OpenThermochronology](https://github.com/OpenThermochronology), that contains repositories of useful code for various tasks written in a variety of programming languages. Some of these programs already have a user base and all meet open science standards. Although OpenThermochronology presents an obvious starting point for community efforts, we suggest that a more complete solution would be integration of the various packages and bits of code present there (and elsewhere) into a set of flexible libraries, coupled with raising awareness of them and their use via a community website (see the Computational Infrastructure for Geodynamics [software](https://geodynamics.org/software) page, or [LandLab](https://landlab.csdms.io/) as mature examples of this). Combined, these would provide helpful entry points for the community; these efforts would both engage new members of the community who may be less familiar with GitHub and encourage more experienced users to contribute to the OpenThermochronology organization.

# Aims

At the broadest level, this initiative aims to provide open-source tools and resources for handling thermochronometer data that are accessible and useful to both new users and experienced programmers writing their own codes. To start, we aim to establish a new community-oriented software library modeling thermochronometer data and a community website for sharing other software and learning resources. The core of many, if not all, of the existing software packages for thermochronology is a set of functions used to combine a thermal history and some mineral data to predict thermochronometer ages, fission-track length distributions, etc. The goals of the new software library would be to:

- Provide useful tools for predicting thermochronometer ages 
- Establish and maintain a repository of kinetic parameters for age prediction algorithms 
- Offer some commonly used data plotting tools (e.g., fission track length distribution plots, (U-Th)/He date-eU plots, Ar/Ar MDD plots) 
- Allow output of: 

    - Files with standardized table formats for publication and/or archiving 
    - Input files that can be read by existing software tools such as HeFTy, Pecube, QTQt, and Thermochron.jl. We want this library to interface well with existing inversion software; the goal is not to rethink these approaches.
    - Include tools for data reduction

Beyond the planned library, we hope that this initiative will further engage the broader community through workshops, user training resources, sharing of resources on a community website, etc.

# Some considerations

Although some decisions such as producing an open-source software library are quite clear, others require consideration and careful planning to ensure as many users as possible benefit. We have provided an outline below of some key discussion points that require community buy-in at the outset. These points could be refined in an OpenThermochronology workshop at an international meeting (Thermo2027, for example) to establish the foundation of how the organization could function.

- An important consideration early on is the programming language used for the new software library (and other new software). We do not suggest using a compiled language such as C, C++, and FORTRAN because it requires users to build the software locally, which already presents a barrier to use. Thus, the preferred languages for use would be Julia or Python. Both allow users to use the code via Jupyter notebooks, where detailed text explanations can guide users through software use. The other pros and cons of each boil down to a few points:

    - Python is one of the most widely used (and taught) programming languages today, while the Julia user base is growing.
    - Julia is faster in almost all cases. Speed may not be a big consideration for single forward models but matters for inverse modeling and models involving many ages.

    This already leads to two related questions: 1) Do we write a library for the broadest set of users, or one that performs better? 2) How do we anticipate changing language preferences (i.e. Python is more popular now, but Julia may overtake it in the future)?

    - We need to clarify the core functionalities of the new library. For example, if the aim is to predict thermochronometer ages, then it makes sense to have a diffusion solver and possibly a Dodson-like closure temperature calculator. But what other essential tools would serve the largest number of people, both as users of the code and developers who use the library in their software? What data should be input and output, and in which format? 
    - What are the common data reduction, analysis, and visualization tools desired by the majority of the community? Should we, for example, develop data handling tools that can output publication-ready tables following the guidelines of Flowers et al. (2022)? Should we also promote use of other software packages by providing options to output files that can be used as inputs for other software such as HeFTy and/or QTQt?
    - How do we design the software library to enable users to easily contribute their own tools and functions into it? Who oversees the process of integration of the new functionalities? How to we make things easy for contributors while still ensuring nothing gets broken? Do we organize workshops for developers (or run webinars) that can demonstrate how to contribute? 

# Next steps

We are currently planning some introductory meetings to be held at major geoscience conferences (e.g., AGU, EGU, and GSA). More information about these introductory meetings will be posted on this site once available.