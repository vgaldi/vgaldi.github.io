---
layout: project
title: "Ray-chaotic “billiard” cavities"
description: Ray chaos, cavity, high frequency, short pulse, billiard
tagline: Billiard cavities
image-icon: /assets/images/projects/billiard_cavity.png
image-text: /assets/images/projects/billiard_cavity1.png
raychaos: true
tags: [ray chaos, cavities, high-frequency, short-pulse]
---
{% include JB/setup %}

Ray chaos, i.e., exponential sensitivity of ray trajectories to launching conditions, 
could intuitively be expected in very complex and cluttered propagation scenarios 
(e.g., urban areas). Remarkably, it can also be observed in relatively simple (but coordinate-non-separable) 
structures that give  rise to multiple reflections, focusing, and defocusing, such as 
homogeneously filled “billiard-shaped” enclosures. 

In [{% cite IJ30_IEEE_APMAG_47_62_2005 %}], by revisiting a body of results from quantum physics (classical vs. quantum chaos),
we emphasized possible implications of internal ray chaos for high-frequency wave dynamics (“ray-chaotic footprints”).
In the time-harmonic high-frequency limit, ray-chaotically-inclined systems tend to exhibit behaviors that differ fundamentally 
from those observed in ray-regular geometries.
For instance, in connection with the eigenvalues, in regular billiards 
the normalized neighboring spacing statistics follow a Poisson probability density function (PDF), 
whereas in completely ray-chaotic billiards, they turn out to be accurately modeled by a Wigner-Rayleigh PDF.
In connection with the eigenfunctions, in regular billiards, 
the wavefield at each point results from the superposition of plane waves (rays) from a finite number of 
possible directions, whereas in completely ray-chaotic billiards it is expected to be a superposition of 
a multitude of plane waves, with fixed wavevector amplitude, and uniform direction and phase distribution.

In [{% cite IJ100_IEEE_TAP_60_3827_2012 %}], we carried out a full-wave investigation of 
short-pulse electromagnetic wavepacket propagation in ray-chaotic enclosures, 
via a numerical approach based on the finite difference time domain (FDTD) method.
 
The figure top panel shows the quarter-Sinai-stadium configuration considered, with a 
typical space-filling ray trajectory (after 250 reflections), and a map illustrating 
the uniform filling of the phase-space (reflection position vs. direction).

The bottom panels show instead the temporal evolution of a short-pulsed wavepacket launched in the cavity.
While bouncing around the walls, along the ray path skeleton, the wavepacket undergoes focusing at the concave 
curved wall and natural spreading elsewhere (including straight-wall reflection), 
progressively losing its initial space-time localization. 
At a sufficiently long time, the wavepacket has already uniformly covered the entire enclosure, and the initially localized energy 
is spread across the mode spectrum.

Results from statistical analysis of the late-time spatial field distributions are 
consistent with the assumption of a random pulsed plane-wave model.

These results may find important applications
to wideband electromagnetic interference and/or compatibility testbeds
(whereby an equipment under test may be subjected to a “pulse
shower” illumination with characteristics largely independent
of its location, orientation, shape and constitutive properties),
as well as the synthetic emulation of multi-path wireless channels.

## Relevant papers
{% bibliography --cited_in_order %}