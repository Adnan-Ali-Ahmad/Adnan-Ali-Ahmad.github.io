---
permalink: /
title: "Star formation with unprecedented fidelity"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

At the Center for Astrophysical Research (CRAL) of ENS Lyon, I investigate the earliest stages of star and planet formation through high-performance computational astrophysics. By carrying out high-resolution simulations that self-consistently model gravity, radiation transport, and magnetic fields, I study the physical processes governing the formation and evolution of protostars and circumstellar disks. My research specifically targets the critical inner region (sub-AU scales) to understand the initial conditions for star and planet formation, as well as the dynamics of the star-disk connection.

My research directly addresses several long-standing challenges in astrophysics, including the angular momentum problem, the magnetic flux problem, the luminosity problem, and the disk mass problem. My work also extends to planetology, in which I offer insights on the transport of high-temperature condensates in the early solar system, thus allowing us to better interpret the composition of meteorites. My simulations incorporate advanced numerical techniques and leverage high-performance computing to achieve unprecedented fidelity in modeling these complex and highly non-linear astrophysical processes.

Below is a curated gallery of my work:

The Method: Adaptive Mesh Refinement (AMR)
======

Simulating the birth of stars and disks presents a formidable numerical challenge, requiring a model that couples highly non-linear physics with an immense dynamic range. My simulations span over 17 orders of magnitude in density ($$10^{5}~-10^{22}\ \mathrm{cm^{-3}}$$) and 8 orders of magnitude in spatial extent ($$10^{4}~-10^{-4}\ \mathrm{AU}$$). To tackle this challenge, I employ Adaptive Mesh Refinement (AMR), which selectively increases resolution in collapsing regions. The animation below illustrates this dynamic range: the color map shows the gas column density, while the white contours trace the AMR levels, highlighting how the simulation adapts to resolve relevant structures across different scales.
<video controls width="100%">
    <source src="/files/the_great_zoom.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>

Birth of protostars and circumstellar disks
======
While disks are often studied in their evolved stages as planet-forming environments, my simulations tackle their initial formation via the gravitational collapse of a gas and dust cloud. By modeling the full dynamical range of the first and second collapse (Larson 1969), these simulations self-consistently form both the protostar and the circumstellar disk, providing a first-principles framework for their detailed study.

![Editing a Markdown file for a talk](/files/MHD_3D.png)

Brown Dwarf Formation
======

Below, you can find a 3D animation showcasing the first month after the formation of a Brown Dwarf through gravitational collapse. Born with a radius of $$\approx 0.75\ \mathrm{R_{\odot}}$$ and mass $$\approx 0.8\ \mathrm{M_{Jup}}$$, it quickly grows by accreting from its surroundings. Angular momentum accretion also causes it to flatten along its equatorial regions.
<video controls width="100%">
    <source src="/files/output_timed.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>

Analyzing the radiative efficiency of protostellar shock fronts
======

![Editing a Markdown file for a talk](/files/lum_problem.pdf)

CAI condensation
======

