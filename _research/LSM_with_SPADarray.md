---
title: "Laser-Scanning Microscopy with SPAD Array Detector"
type: LSM with SPAD array
collection: research
date: 2016-04-01
author_profile: false
sidebar:
  nav: "Tech"
header:
  teaser: LSM_with_SPADarray.jpg
layout: archive
---

<figure style="width: 50%" class="align-center">
<img src='/images/SinglePhotonsMicroscopy.jpg'>
<figcaption>Comparison between laser-scanning microscopy with typical single-element detecor and SPAD array detector.</figcaption>
</figure>

<body align="justify">
Laser-scanning microscopy is one of the most common architecture in fluorescence microscopy, e.g., confocal, two-photon excitation (TPE), and stimulated emission depletion (STED) microscopy. In a nutshell: (i) the objective lens focuses the laser beam(s) to the sample and generates an effective excitation spot which is raster scanned across the sample; (ii) for each position/pixel the fluorescent image of the spot is projected into a single- element detector, which – typically – spatially and temporally integrates the fluorescent light over the detector sensitive area and during the pixel dwell-time, thus providing a single-intensity value per pixel; (iii) all pixel intensity values are registered to build up a digital image. It is clear that the spatio-temporal integration performed by the single-element detector hinders any additional information potentially encoded in the dynamic and image of the fluorescent spot.
To address this limitation, we recently upgraded the detection unit of a laser-scanning microscope, replacing the traditional single-element detector with a novel SPAD (single photon avalanche diode) array detector. In essence, this new detector opens to a new acqisition paradigm for laser-scanning microscopy, where the fluorescent signal for each pixel is collect photon-by-photon and each photon is tagged with a temporal and spatial signature: the arrival-time with respect to a reference time (e.g. the sync of a pulsed laser) and the positon within the iamge of the effective ecitation spot. 
**Scope of this project is to use this new single-photon information to improve the spatiotemporal characteristics of laser-scanning microscopy and to augemt its information content.** 

{% include publication-list-theme.html %}
