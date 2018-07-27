---
layout: project
title: "Nonreciprocal metamaterials"
description: Nonreciprocal, metamaterial, tunneling, isolator, Faraday effect, magneto-optical-effect
tagline: Nonreciprocal
image-icon: /assets/images/projects/nonreciprocal_MTM.png
image-text: /assets/images/projects/nonreciprocal_MTM1.png
MTM: true
tags: [metamaterials, nonreciprocal, tunneling, isolators, Faraday rotation, magneto-optical effect]
---
{% include JB/setup %}

Nonreciprocal light propagation effects are of great interest
in order to design devices such as isolators and circulators that can 
prevent undesired backward reflection and interference effects in optical circuits.
A typical way to attain such effects relies on magneto-optical 
materials which, in the presence of a (static) bias magnetic field that breaks 
the time-reversal symmetry, are characterized by different propagation constants for 
circularly polarized waves with right- and left-handedness. 
However, the magneto-optical activity of candidate materials, such as bismuth iron garnet,
 is quite weak at optical frequencies, thereby leading to rather bulky implementations. 
 Therefore, several strategies have been explored in order to achieve significant response enhancements, 
 all essentially based on the coupling of magneto-electric effects with resonant phenomena.

In some recent investigations, in collaboration with [Nader Engheta] (University of Pennsylvania) and
[Andrea Alù] (University of Texas at Austin), we have explored the 
unidirectional resonant photon tunneling through heterostructures containing magneto-optical constituents.
Our ideas essentially rely on the large body of results available on 
[resonant photon tunneling] phenomena in multilayered heterostructures 
combining single-negative (i.e., with negative permittivity or permeability) and double-positive 
(i.e., with positive permittivity and permeability) material constituents. 
By inserting in these heterostructures magneto-optical materials, 
we render the resonance conditions sensitive to the circular polarization handedness.


More specifically, in [{% cite IJ108_JPD_47_025002_2014 %}], we studied the resonant tunnelling effects that can occur in 
trilayer structures featuring a 
dielectric layer sandwiched between two magneto-optical-metal (e.g., \\(Co_6Ag_{94}\\)) layers. 
We showed that the resonance splitting associated with these phenomena can be exploited to enhance 
Faraday rotation at optical frequencies. Our results indicate that, in the presence of realistic loss levels, 
a tri-layer structure of subwavelength thickness is capable of yielding sensible (∼10◦) 
Faraday rotation with transmittance levels that are an order of magnitude larger than those 
attainable with a standalone slab of magneto-optical-metal metal of the same thickness.

In [{% cite IJ110_JAP_115_043107_2014 %}],
we showed that tri-layer structures combining epsilon-negative and 
magneto-optical material layers can exhibit unidirectional resonant photon 
tunneling phenomena that can discriminate between circularly polarized waves of 
given handedness impinging from opposite directions, or between circularly polarized waves with different handedness 
impinging from the same direction. 
The figure top panel illustrates the configuration considered, consisting of a magneto-electric layer sandwiched 
between two epsilon-negative layers.
The bottom panel shows the resonant field distributions of electric (solid) and magnetic (dashed) fields 
for right-handed circularly polarized plane-wave illumination
impinging from left and right. For incidence from left,
total transmission is clearly visible, with evanescent field growth in the left epsilon-negative layer, 
and the electric and magnetic fields peaked at the center of the magneto-optical layer and at its boundaries 
with the epsilon-negative layers, 
respectively. The response resembles that of a Fabry-Perot resonant cavity, effectively 
formed by the highly reflective properties of the epsilon-negative end layers. Conversely, for incidence from right,
a strong reflection and very low transmission are observed.
Our results indicate that this phenomenon is satisfactorily robust with respect to unavoidable nonidealities, 
and can be exploited to design compact (wavelength-sized) optical isolators for circularly polarized waves. 

[resonant photon tunneling]: /projects/MTM_anomalous-transmission
[Nader Engheta]: https://www.seas.upenn.edu/~engheta/)
[Andrea Alù]: http://users.ece.utexas.edu/~aalu/)


## Relevant papers
{% bibliography --cited_in_order %}