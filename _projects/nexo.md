---
layout: page_with_biblio
title: nEXO
description: Next-generation search for neutrinoless double beta decay in <sup>136</sup>Xe.
img: assets/img/nexo_sensitivity_mbb_vs_mmin.jpg
importance: 1
project_tag: nEXO
category: Ongoing
---

### <strong>The mystery of neutrino masses</strong>

 In the original formulation of the Standard Model (SM) they were assumed to be
massesless, and indeed, the [most sensitive experimental attempts to “weigh” neutrinos](https://www.nature.com/articles/s41567-021-01463-1) have measured masses consistent with zero. However, the phenomenon of neutrino flavor oscillations requires that, while they are extremely light, at least two of the neutrino masses are nonzero. The origin of tiny neutrino masses is a profoundly important topic in fundamental physics. 

The standard mathematical description of mass is known as a “Dirac” mass term, which defines an interaction between a particle and the Higgs boson. However, purely Dirac-type neutrino masses would require 1) the existence of right-handed neutrinos, which have never been experimentally detected and 2) a fine-tuning of the neutrino-Higgs interaction strength with a precision of one part in 10<sup>13</sup>. Instead, <strong>the most compelling theoretical explanations for neutrino
masses add what is known as a Majorana neutrino mass term to the SM</strong>, which can naturally give neutrinos
very small masses while avoiding finely tuned parameters and experimental constraints. 

What makes this exciting is that <strong>Majorana neutrinos would be a fundamentally new object in nature:</strong> they would be equivalent to their own antiparticles and would obtain mass through a mechanism other than the standard Higgs mechanism. Such a discovery would be a foundational change in our understanding of matter. Most importantly, the interactions of Majorana neutrinos would violate a SM symmetry known as “lepton number.” Quantum field theories like the Standard Model are defined by their symmetries; the observation of lepton number violation would provide an important clue as to what deeper, more fundamental description of physics might lie beyond.

The most sensitive experimental test of the Majorana neutrino hypothesis is the search for a never-
before-observed form of radioactive decay called neutrinoless double beta decay (0&nu;&beta;&beta;). Only possible in certain even-even nuclei, 0νββ is a process by which two neutrons in the nucleus simultaneously decay to protons without the emission of neutrinos. If observed, its detection would be immediate proof of the Majorana nature of neutrinos and evidence of new physics. Over the next decade, efforts worldwide will search for this process in O(tonnes) of various candidate isotopes, with
significant potential for making a discovery.




### <strong>The nEXO search for neutrinoless double beta decay</strong>


<div class="row">
    <div class="col-sm-7 mt-3 mt-md-0">
        I work on the nEXO experiment, a next-generation search for 0&nu;&beta;&beta; in the isotope <sup>136</sup>Xe, to be located at the SNOLAB research facility in Sudbury, ON. nEXO will use a five-ton, isotopically enriched liquid xenon time projection chamber (TPC) to detect the two-electron final state of the 0&nu;&beta;&beta; process. The TPC is effectively a large, 3D digital camera for particle interactions: the combination of the light and charge signals is used to reconstruct an image of individual energy depositions with millimeter-scale position resolution, allowing excellent multivariate signal/background discrimination. nEXO is designed to reach a sensitivity to 0&nu;&beta;&beta; decay half-lives up to 1.35x10<sup>28</sup> years, approximately two orders of magnitude beyond the reach of the best currently-operating experiments. 
    </div>
    <div class="col-sm-5 mt-3 mt-md-0">
        <div class="col-sm mt-3 mt-md-0">
            {% include figure.html path="assets/img/nexo-schematic-full.jpg" title="LUX" class="img-fluid rounded z-depth-1" %}
        </div>
        <div class="caption">
            Schematic of the nEXO detector, showing the TPC inside the water shield. The entire assembly will be built 2km underground at SNOLAB.
        </div>
    </div>
</div>




As a postdoc, my efforts were mainly focused in three areas:
<ul>
    <li>
        <strong>Statistical estimation of nEXO's sensitivity</strong> to 0&nu;&beta;&beta; under different assumptions about detector performance and backgrounds
    </li>
    <li>
        <strong>Developing new calibration techniques</strong> using radioisotopes that can be dissolved directly into the liquid xenon detetor medium
    </li>
    <li>
        <strong>Experimental tests of prototype scintillation and ionization readout schemes</strong> that are being developed for nEXO, using the liquid xenon test platforms at Stanford University
    </li>
</ul>

In my new position at SLAC, I am expanding my role in all of these areas, with a particular focus on the ionization readout technology. I am also exploring new applications of nEXO in particle astrophysics, particularly in solar neutrino and dark matter detection. This latter effort is coupled to my work on [nuclear reaction measurements in <sup>136</sup>Cs.](/projects/tunl_cs136)

For information about nEXO, please visit [https://nexo.llnl.gov/](https://nexo.llnl.gov/).

<br> 

### <strong>Collaborators</strong>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/nexo_world_map.png" title="LUX" class="img-fluid rounded z-depth-1" %}
    </div>
</div>



<!-- 
Detecting these extremely rare events requires extreme control of backgrounds, which are primarily
comprised of gamma rays produced by naturally occurring ambient radioactivity. Great care is taken to reduce
these backgrounds via extensive shielding and the selection of extremely low-radioactivity raw materials for
detector construction. While these efforts reduce backgrounds to many orders of magnitude below ambient
levels, they are still too high to detect 0&nu;&beta;&beta;. The key to nEXO’s success is the 3D imaging capability of the liquid
xenon TPC, which enables a multi-variate analysis that provides powerful discrimination between the remaining
backgrounds and a possible signal. The three parameters used in nEXO’s analysis are:
    1. <b>Energy</b>, which will be reconstructed with a resolution (s/E) of better than 1%. 0&nu;&beta;&beta; events form a peak exactly at Q = 2.457 MeV, which can be resolved from most backgrounds.
    2. <b>Event topology</b>, which enables discrimination between single-site 0&nu;&beta;&beta;-like events and multi-site events produced by Compton-scattering gamma rays. nEXO’s image-reconstruction analysis uses a deep neural network (DNN) to discriminate between these two classes of events.
    3. <b>Event distance from detector edges (a.k.a. “standoff”).</b> Background gamma rays are attenuated in the outer regions of the detector, while 0&nu;&beta;&beta; events are uniformly distributed. The signal-to-background ratio therefore increases with the distance from the edges, with the center of the detector being highly sensitive to 0&nu;&beta;&beta;.

The expected distribution of events along each of these three
dimensions is illustrated in Figure 1. The shaded blue region
represents a hypothetical 0&nu;&beta;&beta; signal, while the grey, red, and purple
distributions represent various backgrounds. The signal/background
ratio is maximized near Q = 2.457 MeV and at high values of the DNN
and the standoff, allowing a powerful multi-variate detection of new physics. 
-->