---
layout: project
title: "Non-Hermitian metamaterials"
description: Non-Hermitian, metamaterials, perity-time symmery, transformation optics, beams, leaky waves
tagline: Non-Hermitian
image-icon: /assets/images/projects/non-Hermitian_MTM.png
image-text: /assets/images/projects/non-Hermitian_MTM1.png
MTM: true
tags: [metamaterials, metasurfaces, non-Hermitian, parity-time symmetry, transformation optics, beams, leaky waves]
---
{% include JB/setup %}

*Parity-time* (PT) symmetry is a fascinating concept introduced in quantum physics in order to make sense of *non-Hermitian* Hamiltonians.
This concept, however, is rather general and pervasive, and has resonated in several research communities, triggering a surge of interest
in the study of more general non-Hermitian systems. 

In particular, thanks to the well-known formal analogies between quantum mechanics and (paraxial) optics,
non-Hermitian concepts can be translated to electromagnetic structures by means
of spatial modulation of loss and gain, which is becoming technologically viable
in artificial materials and metamaterials. In fact, in metamaterial engineering, the
introduction of material constituents featuring gain is a well-established strategy
to overcome the inevitable presence of losses. Nonetheless, the above ideas have
inspired novel, unconventional ways of mixing material constituents featuring loss
and gain, so as to attain a wealth of anomalous light-matter interactions that extend
well beyond the mere loss-compensation effects.

In a series of recent investigations, we have been concerned
with the study of field-manipulation and wave-guiding properties of non-
Hermitian metamaterials.

In particular, in [{% cite IJ104_PRL_110_173901_2013 %}] and [{% cite IJ118_JO_18_044027_2016 %}], 
we proposed a complex-coordinate extension of the [transformation-optics] framework that allows to handle complex-valued constitutive parameters
(typical of non-Hermitian metamaterials), while retaining an insightful geometrical
interpretation in terms of the *complexification* of geometrical objects.
In particular, in conjunction with the complex source-point formalism, this approach can naturally handle
the manipulation of beam-like wave objects in the presence of loss and gain. Moreover,
it can also be applied to the manipulation of leaky waves.

In a series of subsequent studies, we have focused on some interesting *tunneling* [{% cite IJ111_PRB_89_085105_2014 %}] and 
*wave-guiding* [{% cite IJ114_PRB_91_115114_2015 %}, {% cite IJ121_PRA_94_043838_2016 %}] phenomena that can be 
induced in non-Hermitian bi-layer and tri-layer systems.
More specifically, in connection with bi-layer systems (as schematized in the figure top panel), we showed that the PT-symmetry condition
inherently yields *unattenuated propagation* along the gain-loss interface, sustained
by a transverse component of the power flux (from the gain to loss region).
The figure bottom panels show the field distribution, exponentially localized at the gain-loss interface.
In particular, we showed that in the *epsilon-near-zero* regime (i.e., vanishingly small real part of the permittivities)
the gain/loss level necessary to sustain the wave confinement and guiding effects can
be significantly reduced.

Overall, such wave-guiding mechanism looks quite attractive in a perspective of
wave-guiding on demand. For instance, one could envision the deploying of gain medium
channels in a lossy background, and their selective enabling (and possibly
reconfiguring) via optical pumping or other gain-inducing mechanisms.

In a related investigation [{% cite IJ113_SREP_5_8568_2015 %}], 
we applied the *supersymmetry* concept to the design of non-Hermitian optical couplers with 
higher-order mode-selection functionalities, 
with potential applications to mode-division multiplexing in optical links.

More recently, in collaboration with [Andrea Alù]'s Group (University of Texas at Austin),
we have explored cylindrical lensing systems composed of pairs of metasurfaces with suitably tailored non-Hermitian
and nonlocal properties in order to attain *magnified
imaging* with reduced aberrations [{% cite IJ123_PRB_95_115114_2017 %}].

In collaboration with [Filippo Capolino]'s Group (University of California at Irvine), we have
also explored the emergence of *exceptional points* in non-Hermitian photonic coupled chains of scatterers 
[{% cite IJ125_PRB_95_104305_2017 %}]. 

Our results may find potentially intriguing applicability to a variety of exotic
light-matter interaction effects (e.g., unidirectional invisibility, coherent
perfect absorption, lasing, negative refraction and focusing, cloaking), and may set the stage for the development of novel
optical components and devices.

[transformation-optics]: /projects/TO-MTM
[Andrea Alù]: http://users.ece.utexas.edu/~aalu/)
[Filippo Capolino]: http://capolino.eng.uci.edu

## Relevant papers
{% bibliography --cited_in_order %}