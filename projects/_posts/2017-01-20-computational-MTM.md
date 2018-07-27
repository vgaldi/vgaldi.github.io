---
layout: project
title: "Metamaterial-based analog computing"
description: Analog computing, metamaterial, metasurface, image processing
tagline: Analog computing
image-icon: /assets/images/projects/computational_MTM.png
image-text: /assets/images/projects/computational_MTM1.png
MTM: true
tags: [metamaterials, metasurfaces, analog computing, image processing]
---
{% include JB/setup %}


In collaboration with the Groups led by [Nader Engheta] (University of Pennsylvania) 
and [Andrea Alù] (University of Texas at Austin), we
have put forward a general paradigm of “metamaterial analog computing” [{% cite IJ109_Science_343_160_2014 %}], 
in which properly designed metamaterial blocks may perform ubiquitous mathematical operations, 
such as spatial differentiation, integration or convolution, on the profile of the impinging light as 
it propagates through them (see the conceptual schematic in the figure top panel).

Our idea is inspired by the earlier “calculating machines” in the form of mechanical, electronic, and hybrid analog computers, 
which have been designed in the past to perform prescribed mathematical computations. 
These solutions suffered from substantial limitations, including relatively large size and slow response, 
and were quickly dropped with the advances on digital computers. 

The figure bottom panel illustrates a possible application of our proposed 
“computational metamaterials” as a Laplace filter for edge detection, 
an increasingly common image processing technique that helps software find faces and identify objects in pictures.

These structures may be of subwavelength size, and several orders of magnitude smaller than conventional 
lens-based optical signal processing systems. 
 In particular, we have proposed two possible architectures: specially designed subwavelength metasurfaces that 
 operate in the spatial Fourier domain, combined with graded-index (GRIN) slabs or fibers; 
 and layered metamaterials that engineer the desired operator’s Green's function directly in the space domain.

These results (included as one of the Highlights in Optics in 2014 in [“Optics & Photonics News”]) may pave 
the way to a re-birth of optical analog computers, but at the nanoscale, 
entirely wave-based, integrable with nanophotonics and electronic, with potentially disruptive applications 
to several fields of science and engineering.

A particularly intriguing follow-up would be the design of metadevices capable of solving
 differential and/or integral equations. 

[Nader Engheta]: https://www.seas.upenn.edu/~engheta/)
[Andrea Alù]: http://users.ece.utexas.edu/~aalu/)
[“Optics & Photonics News”]: http://www.osa-opn.org/home/articles/volume_25/december_2014/extras/doing_math_with_light/

## Relevant papers
{% bibliography --cited_in_order %}