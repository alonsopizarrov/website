---
title: A comparison of tools and techniques for stabilising unmanned aerial
  system (UAS) imagery for surface ﬂow observations
publication_types:
  - "2"
authors:
  - Robert Ljubicic
  - Dariia Strelnikova
  - Matthew T. Perks
  - Anette Eltner
  - Salvador Peña-Haro
  - admin
  - Silvano Fortunato Dal Sasso
  - Ulf Scherling
  - Pietro Vuono
  - Salvatore Manfreda
doi: 10.5194/hess-25-5105-2021
publication: in *Hydrology and Earth System Sciences*
publication_short: HESS
abstract: While the availability and affordability of unmanned aerial systems
  (UASs) has led to the rapid development of remote sensing applications in
  hydrology and hydrometry, uncertainties related to such measurements must be
  quantified and mitigated. The physical instability of the UAS platform
  inevitably induces motion in the acquired videos and can have a significant
  impact on the accuracy of camera-based measurements, such as velocimetry. A
  common practice in data preprocessing is compensation of platform-induced
  motion by means of digital image stabilisation (DIS) methods, which use the
  visual information from the captured videos – in the form of static features –
  to first estimate and then compensate for such motion. Most existing
  stabilisation approaches rely either on customised tools developed in-house,
  based on different algorithms, or on general purpose commercial software.
  Intercomparison of different stabilisation tools for UAS remote sensing
  purposes that could serve as a basis for selecting a particular tool in given
  conditions has not been found in the literature. In this paper, we have
  attempted to summarise and describe several freely available DIS tools
  applicable to UAS velocimetry. A total of seven tools – six aimed specifically
  at velocimetry and one general purpose software – were investigated in terms
  of their (1) stabilisation accuracy in various conditions, (2) robustness, (3)
  computational complexity, and (4) user experience, using three case study
  videos with different flight and ground conditions. In an attempt to
  adequately quantify the accuracy of the stabilisation using different tools,
  we have also presented a comparison metric based on root mean squared
  differences (RMSDs) of inter-frame pixel intensities for selected static
  features. The most apparent differences between the investigated tools have
  been found with regards to the method for identifying static features in
  videos, i.e. manual selection of features or automatic. State-of-the-art
  methods which rely on automatic selection of features require fewer
  user-provided parameters and are able to select a significantly higher number
  of potentially static features (by several orders of magnitude) when compared
  to the methods which require manual identification of such features. This
  allows the former to achieve a higher stabilisation accuracy, but manual
  feature selection methods have demonstrated lower computational complexity and
  better robustness in complex field conditions. While this paper does not
  intend to identify the optimal stabilisation tool for UAS-based velocimetry
  purposes, it does aim to shed light on details of implementation, which can
  help engineers and researchers choose the tool suitable for their needs and
  specific field conditions. Additionally, the RMSD comparison metric presented
  in this paper can be used in order to measure the velocity estimation
  uncertainty induced by UAS motion.
draft: false
featured: false
tags:
  - UAS
categories:
  - UAS
projects:
  - HARMONIOUS
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
date: 2021-09-22T13:24:17.953Z
---
{{% callout note %}}
open-access research paper! 

You can read the manuscript [here](https://doi.org/10.5194/hess-25-5105-2021)
{{% /callout %}}