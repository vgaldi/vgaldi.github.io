---
layout: project
title: "Laser beam shaping"
description: Gravitational wave, mirror, beam
tagline: Beam shaping
image-icon: /assets/images/projects/GW_beam-shaping.png
image-text: /assets/images/projects/GW_beam-shaping1.png
GW: true
tags: [gravitational waves, mirrors, beams, Fabry-Perot, interferometers]
---
{% include JB/setup %}


In addition to the geometric optimization of the [coating design],
suitable shaping of the laser beam has also been proposed as an effective device to reduce internal (mirror) thermal noise 
in advanced gravitational-wave interferometric detectors. 
With specific reference to [Advanced LIGO], the use of *flat-top* (commonly referred to as “mesa”) beams 
has been explored, intuitively motivated by the potential capability of such a beam to better average 
the thermally induced mirror surface fluctuations as compared to a 
standard Gaussian beam. This has been numerically proved to yield significant reductions in the overall 
thermal noise and has
led to the development of a cavity prototype with non-spherical “Mexican hat” profile mirrors. 

In [{% cite IJ35_PRD_73_127101_2006 %}], we investigated the analytic structure of a family of *hyperboloidal* 
beams which generalizes the nearly-flat and nearly-concentric mesa beam configurations. 
Capitalizing on certain results from the applied optics literature on flat-top beams, 
we derived a physically-insightful and computationally-effective representation in terms of rapidly-converging 
Gauss-Laguerre expansions. 
We also worked out a generalization (involving fractional Fourier transform operators of complex order) 
of some duality relations between the nearly-flat and nearly-concentric mesa 
configurations.

In [{% cite IJ47_PRD_76_122003_2007 %}], 
relying on some analytic approximations (valid in the infinite-test-mass limit) 
for the Brownian and thermoelastic mirror noises in the presence of arbitrary-shaped beams, 
we explored the optimal beam-shaping problem. 
The figure top panel shows the assumed cavity geometry, while the bottom panel illustrates 
the optimal profiles obtained, for the various noise sources. More specifically, \\(q=-1,0,1\\) refer to the substrate Brownian, the coating 
(Brownian and thermoelastic), and the substrate thermoelastic noise, respectively.
With specific reference to [Advanced LIGO], 
we obtained some absolute and realistic lower bounds for the various thermal-noise constituents,
and compared them with the Gaussian- and mesa-beam scenarios.
Our result indicate fairly ample margins for further reduction. 
In this framework, we also identified the effective dimension of the related optimization problem, 
and its relationship to the critical design parameters. Moreover, we considered the physical-feasibility 
and model-consistency issues, and highlighted possible additional requirements and/or prior information exploitable 
to drive the subsequent optimization process.


[coating design]: /projects/GW-coating

[Advanced LIGO]: https://www.advancedligo.mit.edu


## Relevant papers
{% bibliography --cited_in_order %}