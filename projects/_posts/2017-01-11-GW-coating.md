---
layout: project
title: "Optimized mirror coatings"
description: Gravitational wave, mirror, coating
tagline: Mirror coatings
image-icon: /assets/images/projects/GW_coating.png
image-text: /assets/images/projects/GW_coating1.png
GW: true
tags: [gravitational waves, mirrors, coatings, Fabry-Perot, interferometers]
---
{% include JB/setup %}



For second-generation gravitational-wave interferometric detectors such as [Advanced LIGO], 
the thermal noise of the test mass mirror coatings is a significant limit in a critical midband around 100 Hz.
 
The optical cavities at the heart of the length-sensing mechanism of gravitational wave interferometers 
use mirrors made with multilayer dielectric coatings to produce the high reflectivities that are required.
The conventional design of high-reflectivity multilayer dielectric coating consists of quarter-wavelength alternating layers 
made of silica (low-index) and tantala (high-index) materials. Such design, though optimal from the reflectivity viewpoint, 
does not minimize the thermal noise since there is a substantial difference in the mechanical loss of 
the two material constituents.

In [{% cite ISI-000241947200007 %}], we proposed a systematic procedure for designing minimal-noise 
coatings featuring a prescribed reflectivity. Such design is based on a periodic stack of 
identical high/low index ‘‘doublets,’’ with total thickness of half-wavelength and optimized material fractions, 
with the exception of the terminal (top/bottom) layers. 

Mirrors based on such a design were fabricated 
at the Laboratoire des Matériaux Avancés (Lyon, France) and experimentally characterized by measuring 
the broadband noise floor of the Thermal Noise
Interferometer (TNI) at the California Institute of Technology [{% cite IJ86_PRD_81_122001_2010 %}]. 

The figure shows the optimized design (top), and the measured thermal noise (bottom) 
compared with the standard quarter-wavelength design.
The measurements indicated a reduction in thermal noise in line with modeling predictions.

Our optimized mirror coatings have been implemented in Advanced LIGO [{% cite IJ119_PRD_93_112004_2016 %}], and have contributed 
to attain the required strain sensitivity for the direct detection of gravitational waves.


[Advanced LIGO]: https://www.advancedligo.mit.edu


## Relevant papers
{% bibliography --cited_in_order %}