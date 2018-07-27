---
layout: project
title: "Extreme-parameter metamaterials"
tagline: Extreme-parameter
image-icon: /assets/images/projects/extreme-parameter_MTM.png
image-text: /assets/images/projects/extreme-parameter_MTM1.png
MTM: true
tags: [metamaterials, imaging, epsilon near zero, extreme parameter]
---
{% include JB/setup %}

Metamaterials with *extreme parameters* (e.g., very small or very large components of the constitutive 
tensors) are of interest in many important applications.
For instance, metallo-dielectric multilayers characterized by extreme anisotropy 
convert evanescent spectral components with large transverse wavenumbers into propagating waves, thereby
exhibiting intriguing subwavelength focusing effects that are of great interest in imaging applications. 
More recently, the use of obliquely layered structures has been proposed in order to achieve simple 
image manipulation (lateral displacement) with subwavelength resolution. 

With the exception of few cases for which analytical approximations of 
the Green's function can be worked out, the imaging properties (e.g., resolution) 
of the above configurations need to be assessed numerically. 

In a study in collaboration with [Nader Engheta] (University of Pennsylvania) and
[Andrea Alù] (University of Texas at Austin)
[{% cite IJ101_PRB_86_115123_2012 %}], we studied in detail a slab of uniaxial 
*epsilon-near-zero* metamaterial with tilted optical axis, as schematized in the figure top panel
(also shown are the typical elliptic and hyperbolic equifrequency contours in the global 
and rotated spectral reference systems).

In particular, we derived a closed-form analytical solution for the Green's function in terms 
of special cylindrical functions. These functions can be efficiently computed via well-established numerical schemes, 
yielding computational savings up to nearly three orders of magnitudes by comparison with brute-force numerical 
quadrature of the corresponding spectral integrals. Moreover, in the near-field parameter range of interest, 
they can be conveniently approximated in terms of simple analytical functions.
Validation and calibration of our results against a numerical-integration-based reference solution 
confirmed the applicability of our solution to subwavelength imaging scenarios with low-loss constitutive parameters 
that are within reach of current (e.g., gain-assisted) technologies. 
We have employed this solution to analyze the imaging properties of anisotropic epsilon-near-zero metamaterial 
slabs varying the design parameters and tilt angle. The figure bottom panel illustrates some
representative results, in terms of intensity
maps (within and beyond the image plane), for the optical axis angle varying from 0 to 75°
with step of 15°.

Our results shed new light on the subwavelength imaging properties of epsilon-near-zero metamaterial 
slabs and allow tailoring their properties without the need of extensive numerical simulations.


[Nader Engheta]: https://www.seas.upenn.edu/~engheta/)
[Andrea Alù]: http://users.ece.utexas.edu/~aalu/)


## Relevant papers
{% bibliography --cited_in_order %}