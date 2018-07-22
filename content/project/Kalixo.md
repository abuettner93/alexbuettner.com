+++
# Date this page was created.
date = "2018-07-12"

# Project title.
title = "Kalixo Molecular Modeling Framework"

# Project summary to display on homepage.
summary = "The Kalixo molecular modeling framework (KMMF) is a tool for producing a system of interaction potentials for molecular dynamics (MD) using a generalized lattice inversion approach."

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
image = ""
caption = ""

+++
The Kalixo molecular modeling framework (KMMF) is a tool for producing a system of interaction potentials for molecular dynamics (MD) using a generalized lattice inversion approach.  When faced with the task of computing mechanical properties and understanding the dynamical state of a physical system, MD simulations have become the primary means for any reasonably large-scale investigations.  Unfortunately, many materials are not yet characterized by potential energy functions that accurately represent the interactions within the system and reproduce the desired material properties. In these cases, researchers may use *ab initio* simulations (DFT/planewave/periodic systems) to study the system of interest; however, these methods require very expensive calculations and are extremely resource intensive. KMMF is able to produce parameter-free pair-potentials from energetic data generated using high-quality DFT calculations, bridging the gap between the two types of computational experiments.  This provides a pathway for the use of faster MD simulation methods to accurately reproduce materials property data without the need for extended run-times. The idea originated in the PhD thesis of my good friend, Dr. Kevin Schmidt, and has broadened into this project. 

The generated potentials will be of a new kind, so named: **K**alixo **I**nversion **T**echnique **T**o **I**ntegrate **E**lectronic **S**tructure **M**ethods, **E**nabling **O**ptimum **W**orking, or as we call it in the biz, the *KITTIES-MEOW* Potential.


The core of this project is based on the paper [A generalized method for the inversion of cohesive energy curves from isotropic and anisotropic lattice expansions](http://doi.org/10.1039/C5CP03792A) published by Kevin M. Schmidt and Victor R. Vasquez in the journal [Physical Chemistry Chemical Physics](http://pubs.rsc.org/en/journals/journalissues/cp).

<!-- This project is in collaboration with [Charles Coronella](http://www.unr.edu/homepage/coronell/) from [University of Nevada, Reno](http://www.unr.edu/). -->