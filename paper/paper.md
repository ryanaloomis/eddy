---
title: 'Eddy: Extracting Disk Dynamics'
tags:
  - Python
  - astronomy
  - dynamics
  - accretion disk dynamics
  - protoplanetary disks
authors:
  - name: Richard Teague
    orcid: 0000-0003-1534-5186
    affiliation: "1"
affiliations:
 - name: University of Michigan
   index: 1
date:
bibliography: paper.bib
---

# Summary

Planet formation occurs in protoplanetary disks, excess material from the stellar formation phase which, due to conservation of angular moment, orbits the newly born star. The dynamics of this gas should be dominated by the gravitational force of the parental star, however pressure gradients in the gas, three dimensional geometries or the presence of embedded planets will result in significant deviations. The use of spectrally resolved observations of molecular line emission from these disks allows for the study of the gas dynamics and thus allows for constraints on the physical and dynamical processes involved in planet formation.

``Eddy`` is a Python package which implements several methods for extracting kinematical information from astronomical datasets.

``Gala`` is an Astropy-affiliated Python package for galactic dynamics. Python
enables wrapping low-level languages (e.g., C) for speed without losing
flexibility or ease-of-use in the user-interface. The API for ``Gala`` was
designed to provide a class-based and user-friendly interface to fast (C or
Cython-optimized) implementations of common operations such as gravitational
potential and force evaluation, orbit integration, dynamical transformations,
and chaos indicators for nonlinear dynamics. ``Gala`` also relies heavily on and
interfaces well with the implementations of physical units and astronomical
coordinate systems in the ``Astropy`` package [@astropy] (``astropy.units`` and
``astropy.coordinates``).

``Gala`` was designed to be used by both astronomical researchers and by
students in courses on gravitational dynamics or astronomy. It has already been
used in a number of scientific publications [@Pearson:2017] and has also been
used in graduate courses on Galactic dynamics to, e.g., provide interactive
visualizations of textbook material [@Binney:2008]. The combination of speed,
design, and support for Astropy functionality in ``Gala`` will enable exciting
scientific explorations of forthcoming data releases from the *Gaia* mission
[@gaia] by students and experts alike. The source code for ``Gala`` has been
archived to Zenodo with the linked DOI: [@zenodo]

# Mathematics

Single dollars ($) are required for inline mathematics e.g. $f(x) = e^{\pi/x}$

Double dollars make self-standing equations:

$$\Theta(x) = \left\{\begin{array}{l}
0\textrm{ if } x < 0\cr
1\textrm{ else}
\end{array}\right.$$


# Citations

Citations to entries in paper.bib should be in
[rMarkdown](http://rmarkdown.rstudio.com/authoring_bibliographies_and_citations.html)
format.

# Figures

Figures can be included like this: ![Example figure.](figure.png)

# Acknowledgements

We acknowledge contributions from Brigitta Sipocz, Syrtis Major, and Semyeong
Oh, and support from Kathryn Johnston during the genesis of this project.

# References
