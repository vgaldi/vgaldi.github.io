---
layout: project
title: "Reconfigurable metamaterial electric circuits"
description: Reconfigurable, metamaterial, electric circuits, cloaking, phase-change
tagline: Reconfigurable
image-icon: /assets/images/projects/reconfigurable_MTM.png
image-text: /assets/images/projects/reconfigurable_MTM1.png
MTM: true
tags: [metamaterials, reconfigurable, electric circuits, cloaking, phase-change materials]
---
{% include JB/setup %}



When designing an electronic system, the influence of the surrounding environment can be considered either 
a nuisance (and hence something to be suppressed) or a convenient knob that can be turned to affect the material properties. 
In the latter view, an ideal scenario would be to have the system designed in such a way that the external effect 
could be amplified and not only the local material characteristics but also the collective device property 
can be drastically manipulated with environmental stimuli

In a study [{% cite IJ115_PRB_91_134105_2015 %}] in collaboration with the Groups led by [Yuki Sato] and 
[Shriram Ramanathan] (Harvard University), we demonstrated 
for the first time a metamaterial electric circuit integrated onto a silicon wafer that can dynamically 
reconfigure the preferred conduction paths. This is enabled by introducing a correlated electron oxide thin film that undergoes a 
sharp thermally-induced insulator-metal transition in the circuit. 

The tunable metamaterial is designed with the aid of two interwoven 
coordinate-transformation equations and implemented with a network of thin-film resistors and vanadium dioxide (\\(VO_2\\)), 
as shown in the figure top panels. 
The strong temperature dependence of \\(VO_2\\) electrical conductivity results in a significant modification of the resistor network behavior, 
and we provided experimental evidence for a reconfigurable metamaterial electric circuit that not only mimics a continuous medium, 
but is also capable of responding to thermal stimulation through dynamic variation of its spatial anisotropy. 

As shown in the figure bottom panels, upon external temperature change, the overall effective functionality of the material switches between 
a “truncated cloak” and a “concentrator” for electric currents.

These results suggest that the metamaterial paradigm may be used 
to provide solutions for tangible compact electronics using thin-film technologies. 
Traditionally, electronic systems comprise several blocks, each designed to play a specific role. 
A smarter design approach could rely on a single unit capable of handling multiple functions, 
such as carrying electric current and heat simultaneously but independently. 
A potential first step in this direction has been shown recently, 
by using metamaterial structures designed with the framework of [multiphysics transformations]. 
The same goal may be approached through a different path of utilizing phase-change materials that have varying responses 
in different physical domains.

Moreover, our demonstration paves the way for future high performance chips that can be environmentally responsive, 
for instance moving heat away from hot spots in circuits to colder regions by simply being aware of local temperature. 
This can overcome significant constraints that limit innovation in information processing today where heat dissipation is the primary bottleneck.

 
 [Yuki Sato]: http://www2.rowland.harvard.edu/people/yuki-sato
 [Shriram Ramanathan]: http://shriram-ramanathan.org
 [multiphysics transformations]: /projects/multiphysics-MTM
 

## Relevant papers
{% bibliography --cited_in_order %}