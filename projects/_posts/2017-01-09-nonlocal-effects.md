---
layout: project
title: "Nonlocal effects in metamaterials"
description: Dispersion engineering, nonlocal, transformation optics, frozen modes, degenerate band edge, 
tagline: Nonlocal
image-icon: /assets/images/projects/dispersion_engineering.png
image-text: /assets/images/projects/dispersion_engineering1.png
MTM: true
tags: [metamaterials, nonlocal, transformation optics, dispersion engineering, frozen modes, degenerate band edge]
---
{% include JB/setup %}


Spatial dispersion, i.e., the *nonlocal* character of the electromagnetic 
constitutive relationships, is typically regarded as a negligible effect for most natural media. 
However, there is currently a growing interest in its study, in view of its critical relevance in the homogenized 
(effective-medium) modeling of many artificial electromagnetic materials of practical interest, as well as in a variety
 of related effects 
including artificial magnetism, wave splitting into multiple beams, beam tailoring, 
and ultrafast nonlinear optical response. If, for most metamaterials, spatial dispersion is seen as a nuisance, 
counterproductive for practical applications, its proper tailoring and engineering may add novel degrees of 
freedom in the wave interaction with complex materials.

In [{% cite IJ98_PRL_108_063902_2012 %}], in collaboration with 
[Nader Engheta] (University of Pennsylvania) 
and [Andrea Alù] (University of Texas at Austin),
we have extended the [transformation-optics] approach by enabling the manipulation and control of 
*nonlocal* light-matter interactions. 
Instead of spatially-changing refractive properties, we proposed a framework of “transformation media” 
that can tailor the wave interaction in the reciprocal space of spatial wave-numbers, 
so as to produce desired nonlocal effects. 

Subsequently, in [{% cite IJ117_Optica_3_179_2016 %}] and [{% cite IJ120_EPJAM_3_2_2016 %}], we further generalized this approach 
in the frequency-wavenumber reciprocal phase space, so as to engineer a broad variety of nonlocal interactions 
and spatial dispersion effects, including including “one-way” (nonreciprocal) propagation, 
“frozen-mode” and “degenerate-band-edge” regimes, and Dirac-point conical singularities

For instance, the figure top panel illustrates a desired dispersion effect, namely, a degenerate-band-edge condition 
at a prescribed frequency. Such exotic dispersion effect (manifested by 
the appearance of a higher-order stationary point in the dispersion relationship)
is eliciting a growing attention in view of its potential relevance to diverse applications 
including slow light, solid-state lasers, quantum-cascade lasers, sensors, optical delay lines, 
traveling-wave tubes, distributed solid-state amplifiers, and switches.

The figure bottom panel shows the corresponding field distribution in a unit cell of a 
multilayered metamaterial synthesized with our approach.  
As it can be observed, the field is transmitted (with small reflection) in the metamaterial half-space, 
where it gets converted into an extended mode with growing amplitude. 
At a distance of about five wavelengths from the vacuum-metamaterial interface, 
the amplitude reaches a maximum value that is over a factor 1000 larger than the incident one, and 
then it starts decreasing.

A key attribute of our approach, 
similar to conventional transformation optics, 
is the separation of the conceptual design (based on intuitive geometrical considerations) 
from the actual metamaterial synthesis (based on a suitable approximation of analytically derived 
constitutive “blueprints”. 

Our approach may open up new perspectives in the systematic design of metamaterials with broad field-manipulation capabilities as well as complex spatiotemporal dispersion effects, 
with potential applications to nonreciprocal optics, topological photonics, and “[computational metamaterials].”

More recently, in a study [{% cite IJ128_PRB_96_081113_2017 %}] in collaboration with [Carlo Rizza] (University of l'Aquila) 
and [Alessandro Ciattoni] (CNR-SPIN), we have explored a novel class of structures, based *moderate-permittivity* inclusions, for which 
nonlocal effects are enhanced. Among other things, these results may significantly 
boost the practical applicability of nonlocal transformation optics.

In a different, but related, study [{% cite IJ105_PRB_87_235116_2013 %}] we have investigated the emergence of 
[aperiodic-order-induced nonlocal effects] in multilayered metamaterials.

[Nader Engheta]: https://www.seas.upenn.edu/~engheta/)
[Andrea Alù]: http://users.ece.utexas.edu/~aalu/)
[computational metamaterials]: /projects/computational-MTM
[Transformation-optics]: /projects/TO-MTM
[aperiodic-order-induced nonlocal effects]: /projects/aperiodic-ML
[Carlo Rizza]: https://sites.google.com/site/rizzacarlo81/
[Alessandro Ciattoni]: http://www.ing.univaq.it/personale/scheda_personale.php?codice=511

## Relevant papers
{% bibliography --cited_in_order %}