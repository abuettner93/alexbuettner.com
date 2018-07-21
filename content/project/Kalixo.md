+++
# Date this page was created.
date = "2018-07-12"

# Project title.
title = "Kalixo Molecular Modeling Framework"

# Project summary to display on homepage.
summary = "The Kalixo molecular modeling framework (KMMF) is a molecular dynamics analysis tool that is capable of producing pair-potentials for solid-state materials from density functional theory calculation using a generalized lattice inversion approach."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "kalixo_logo1.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["molecular dynamics", "DFT", "inversion",]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "kalixo_logo1.png"
caption = ""

+++
The Kalixo molecular modeling framework (KMMF) is a molecular dynamics analysis tool that is capable of producing pair-potentials for solid-state materials from density functional theory calculations using a generalized lattice inversion approach. With the advent of modern computing, when faced with the task of computing material properties data and operational qualities of a crystalline compound, molecular dynamics simulations are used as a primary investigation tool. However, many materials are not yet characterized by pair-potentials that represent the components of the crystal, nor accurately reproduce the material properties. In these cases, researchers may use *ab initio* simulations (DFT, HF, etc.) to dynamically simulate the compound; but these calculations are extremely resource intensive and require orders of magnitude greater run time. KMMF is able to produce pair-potentials from cohesive energy curves generated using simple (and cheap) DFT calculations, providing a pathway for the use of faster simulation methods (molecular dynamics) to accurately reproduce materials property data without the need for extended run-times. The idea originated in my good friend Dr. Kevin Schmidt's PhD thesis, and has broadened into this project. 

The core of this project is based on the paper [A generalized method for the inversion of cohesive energy curves from isotropic and anisotropic lattice expansions](http://doi.org/10.1039/C5CP03792A) published by Kevin M. Schmidt and Victor R. Vasquez in the journal [Physical Chemistry Chemical Physics](http://pubs.rsc.org/en/journals/journalissues/cp).

<!-- This project is in collaboration with [Charles Coronella](http://www.unr.edu/homepage/coronell/) from [University of Nevada, Reno](http://www.unr.edu/). -->