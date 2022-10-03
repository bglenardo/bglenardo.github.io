---
layout: page_with_biblio
title: nEXO
description: Next-generation search for neutrinoless double beta decay in <sup>136</sup>Xe.
img: assets/img/nexo_sensitivity_mbb_vs_mmin.jpg
importance: 1
project_tag: nEXO
category: Ongoing
---

<i>Under construction</i>

### The mystery of neutrino masses

Neutrinos, which come in three “flavors” (&nu;<sub>e</sub> , &nu;<sub>&mu;</sub> , and &nu;<sub>&tau;</sub>), are the most abundant fundamental fermions and play a pivotal role in forming the structure and composition of the universe we live in today. They
carry no electric charge and interact only via the weak nuclear force, making them exquisite messengers of
subatomic and nuclear physics. In the original formulation of the Standard Model they were assumed to be
massesless, and indeed, the most sensitive experimental attempts to “weigh” neutrinos have measured masses
consistent with zero and shown that they are at least 1,000,000 times lighter than the next lightest massive
particle. However, the Nobel-prize-winning discovery that neutrinos can oscillate between flavors proves that,
while they are extremely light, at least two of the neutrino masses are nonzero.

The origin of tiny neutrino masses is a profoundly important topic in fundamental physics. The standard
mathematical description of mass is known as a “Dirac” mass term, which defines an interaction between a given
particle and the Higgs boson. However, purely Dirac-type neutrino masses would require 1) the existence of
right-handed neutrinos, which have never been experimentally detected, and 2) a fine-tuning of the neutrino-
Higgs interaction strength with a precision of one part in 10<sup>13</sup>. It seems highly suspicious that nature would
choose a fundamental parameter so carefully. Instead, the most compelling theoretical explanations for neutrino
masses add what is known as a “Majorana-type" neutrino mass to the SM, which can naturally give neutrinos
very small masses while avoiding finely tuned parameters and experimental constraints. What makes this
exciting is that Majorana neutrinos would be a fundamentally new object in nature: they would be equivalent to
their own antiparticles and would obtain mass through a mechanism other than coupling to the Higgs field. Such
a discovery would be a foundational change in our understanding of matter. Most importantly, the interactions
of Majorana neutrinos would violate a SM symmetry known as “lepton number.” Quantum field theories like the Standard Model are defined by their symmetries; the observation of lepton number violation would provide
an important clue as to what deeper, more fundamental description of physics might lie beyond.

### Search for neutrinoless double beta decay with nEXO

The most sensitive experimental test of the Majorana neutrino hypothesis is the search for a never-
before-observed form of radioactive decay called neutrinoless double beta decay (0νββ). Only possible in certain
even-even nuclei, 0νββ is a process by which two neutrons in the nucleus simultaneously decay to protons. In
standard beta decay, a single neutron emits an electron and an anti-neutrino. In 0νββ the two antineutrinos would
co-annihilate within the nucleus and only the electrons would be emitted. By creating two leptons and zero anti-
leptons in the final state, 0νββ violates lepton number symmetry. Its detection would be immediate evidence of
new physics and proof of the Majorana nature of neutrinos. Over the next decade, efforts worldwide will search
for this process in O(1) ton of various candidate isotopes, probing deep into unexplored parameter space with
significant potential for making a discovery.

I work on the nEXO experiment, which will search for 0&nu;&beta;&beta; in the isotope <sup>136</sup>Xe. Scaling up the successful techniques developed by the SLAC/Stanford-led EXO-200 experiment, nEXO will use a five-ton, isotopically
enriched liquid xenon time projection chamber (TPC) to detect the two-electron final state of the 0&nu;&beta;&beta; process. Ionizing radiation interacting in the liquid xenon produces both scintillation light and ionized charge, which are
detected by sensors on the outer edges of the cylindrical xenon volume. The TPC is effectively a large, 3D digital
camera for particle interactions: the combination of the light and charge signals is used to reconstruct an image
of individual energy depositions with millimeter-scale position resolution. nEXO is designed to reach a sensitivity to 0&nu;&beta;&beta; decay half-lives up to 1.35 x 1028 years,
approximately two orders of magnitude beyond the reach of the best currently-operating experiments. This
corresponds to a signal rate of just 1.1 decays per year.

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