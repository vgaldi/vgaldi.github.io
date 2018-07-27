---
layout: project
title: "Optical nonlocality in aperiodic multilayered hyperbolic metamaterials"
description: Aperiodic, multilayer, hyperbolic, metamaterial, Thue-Morse, nonlocal
tagline: Multilayers
image-icon: /assets/images/projects/aperiodic_ML.png
image-text: /assets/images/projects/aperiodic_ML1.png
aperiodic: true
tags: [aperiodic, multilayers, hyperbolic, metamaterials, nonlocal]
---
{% include JB/setup %}

Hyperbolic metamaterials are characterized by uniaxally 
anisotropic constitutive relationships with both positive and negative 
components of the permittivity (or permeability) tensor. 
This yields a *hyperbolic* (as opposed to spherical in conventional isotropic media) 
dispersion relationship, which allows for the propagation of (otherwise evanescent) 
waves with large wave vectors, resulting in a high (theoretically unbounded) photonic density of states. 

Typical multilayered implementations of hyperbolic metamaterials are based 
the stacking of alternating subwavelength layers with negative and positive permittivities 
(e.g., metallic and dielectric at optical wavelengths). For this class, the effective-medium theory
 provides a particularly simple model in terms of a homogeneous uniaxially anisotropic 
 permittivity tensor with components given by the Maxwell-Garnett mixing formulas. 
 However, a series of recent papers have pointed out the limitations of this model 
 in predicting nonlocal effects that can take place (even in the presence of deep subwavelength layers) 
 due to the coupling of surface-plasmon polaritons propagating along the interfaces separating 
 layers with oppositely signed permittiv- ities. This may result, for instance, 
 in the misprediction of additional extraordinary waves, as well as of the broadband Purcell effect.
 
 Although the effective-medium-theory model describing the local response is independent of the positional 
 order of the layers and depends only on the permittivities of the two constituents and their filling fractions, 
one would intuitively expect the positional order of the layers to sensibly affect the nonlocal response. 

Within this framework, in [{% cite IJ105_PRB_87_235116_2013 %}], we studied the nonlocal response of hyperbolic metamaterials 
constituted by multilayer superlattices based on the Thue-Morse geometry.
The chosen geometry (schematized in the figure top panel) is particularly interesting since different iteration orders differ solely 
in the positional order of the constituent material layers. Interestingly, we identified some configurations 
for which these nonlocal effects are rather weak at the first two iteration orders 
(corresponding to standard periodic multilayers) and become markedly more prominent at higher 
iteration orders.
From the mathematical viewpoint, these effects can be associated with stationary points of the transfer-matrix 
trace and can be effectively parametrized via the *trace-map* formalism. We showed that their onset is accompanied 
by a strong wave-vector dependence in the effective constitutive parameters, as well as 
the appearance of 
additional extraordinary waves, as shown in the figure center panels. The bottom panels 
illustrate the propagation of such an additional extraordinary wave in a finite-thickness metamaterial slab. 
In particular, the transverse distribution exhibits large amplitude variations and peaks at the interfaces between dielectric
and metallic layers, due to the propagation of surface-plasmon-polaritons.

Despite the inherent periodicity enforced by the unavoidable (Bloch-type) supercell terminations, such strong nonlocality 
is retained at any arbitrarily high-order iteration, i.e., approaching the actual aperiodic regime. 
To the best of our knowledge, against the many implications and applications, 
this represents the first evidence in connection with optical nonlocality. Besides the inherent academic interest, 
from the application viewpoint, this constitutes an important and technologically inexpensive additional 
degree of freedom in the engineering of optical nonlocality, which may also be fruitfully exploited within 
the recently introduced framework of [nonlocal transformation optics].

[nonlocal transformation optics]: /projects/nonlocal-effects




## Relevant papers
{% bibliography --cited_in_order %}