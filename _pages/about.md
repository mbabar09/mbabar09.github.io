---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a PhD candidate in [Prof. Venkatasubramanian Viswanathan's group](https://www.cmu.edu/me/venkatgroup/) in the department of Mechanical Engineering at University of Michigan. My broad interests are in electrochemical kinetics, solid state physics, machine learning and density functional theory in energy materials. 

# Bio
- **PhD Mechanical Engineering, University of Michigan** 2023 - present
- **M.S/Ph.D Mechanical Engineering, Carnegie Mellon University** 2019 - 2023
- **B.Tech Mechanical Engineering, Indian Institute Technology Delhi** 2015-2019

# Research 
- Ab-initio electronic and structural properties of materials 
- Investigation of anionic redox in lithium-rich transition metal oxides 
- Electrochemical kinetics/models in twisted flat band systems
- Machine learning energetics of electrode materials  

# Summary of Thesis

Li-based battery technologies are still in their infancy stage relative to mature lead acid and Ni-Cd batteries. New energy-intensive applications like heavy-duty trucks and electric vertical takeoff and landing (eVTOL) demand significant improvements in active chemistry and innovations in electrode design. In rechargeable Li-ion batteries, the possibilities in design of electrodes are vast and has been a dominant avenue for improving capacity, energy density, reversibility and cycle life. Research efforts in this field are organized around different components of the battery (anode, cathode, electrolyte etc.) and at different length scales i.e. atomic, micro and meso-scales. I have examined notable modifications on electrode design and chemistry, specifically (i) geometric reshaping of layers to accelerate electron transfer, and (ii) atomic remodeling to improve thermodynamic and diffusion properties. To achieve this, I have employed first-principle density functional theory (DFT) that have become increasingly popular for evaluating electrochemical, thermodynamic and kinetic properties of lithium-ion electrodes. My work revolves around two promising classes of electrodes; twisted multilayer graphene and lithium-rich transition metal oxides.

Specifically, I have employed topological flat bands in magic-angle twisted bilayer graphene (1.1 deg) to propose a pathway for greatly enhanced electronic conductivity within a modified rate theory. This result was experimentally validated by our collaborators at UC Berkeley by Dr. Bediako Kwabena and now published in Nature Chemistry. To follow up, I identified an improved performance regime in twisted trilayer graphene due to emergent non-overlapping bands from incommensurate moir’e patterns. Finally, I introduced a new ‘microscopy’ technique to resolve spatial features in twisted bilayer graphene by scanning its electrochemical response over the 2D surface. During this period, I have worked with a DFT-derived tight binding model in MATLAB, electrochemical rate models in Julia, and solved ion-transport in FEniCS (finite element), all parallelized for an optimized use of resources.  

I have also investigated lithium-rich materials as high-capacity electrodes for batteries. In Li-rich vanadium oxide, I analyzed its density of states, crystal orbital overlap projections, and NEB barriers to explain its fast charging mechanism and degradation in high-energy orderings. With a small amount of fluorine doping, we found enhanced cationic redox and structural stability. Later, in collaboration with Northeastern university (Dr. Arun Bansil), we found that in-operando magnetic moments can be used to accurately identify regions of anionic and cationic redox in Li-rich Ni-rich oxides. I also wrote a proposal to request support for this collaboration, and we were fortunate to receive a grant from the Office of Naval Research to pursue this project for three years. 

Throughout this time frame, I have actively employed machine learning methods as an alternative to the compute-intensive DFT. As a benchmark, I used a physics-informed neural network to learn energies of a DFT-calculated lithium-graphite system, and successfully matched its lattice parameters, elastic constants, and open circuit voltage with experimental results. Recently, I have shifted to a more robust and data efficient E(3) equivariant graph neural network architecture (NeqUIP) for learning DFT energies, forces and stresses simultaneously. I have used this architecture in Li-rich systems to train a calculator with a small DFT dataset and plugged it in a Monte Carlo scheme to identify the stable phases for electronic structure study.


# About this site
This website is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub Pages. [GitHub Pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads!
