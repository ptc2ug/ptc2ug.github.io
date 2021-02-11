---
title: Research
feature_text: |
  ## Research
feature_image: "/assets/nobbys_beach.png"
excerpt: "Description of research in Cummings group"
aside: true
---

The research in our group, which is computational in nature, falls into three main categories.

A significant focus of our scientific/engineering research is focused on capacitive energy storage systems - specifically [supercapacitors.](https://en.wikipedia.org/wiki/Supercapacitor "supercapacitors."), described in section 1 below. This research consists of both purely computational studies as well as research that is highly integrated with experiment and synthesis. 

Another major science focus is on transport phenomena at the nanoscale - specifically [friction](https://en.wikipedia.org/wiki/Friction "friction") and [tribology.](https://en.wikipedia.org/wiki/Tribology "tribology.") When two surfaces, separated by distances of the order of nanometers, move with respect to each other, friction must be reduced via a lubricant. The typical lubricants used at the macroscale (e.g., the oil use to lubricates an automobile engine) do not function as lubricants when confined to distances of the order of nanometers. Hence, new lubricants must be discovered, and we aim to do this via molecular simulation. Pleas see section 2 below. 

All of our research is conducted using molecular simulation methods. Molecular simulation is a methodology for predicting the collective (in particular, thermodynamic and transport) properties of systems from information about how the molecules in the system interact with each other; this information is encapsulated in so-called [force fields](https://en.wikipedia.org/wiki/Force_field_(chemistry) "force fields"). Two major types of molecular simulations are routinely performed: molecular dynamics, in which Newton’s equations, or a convenient variation thereof, are solved for the dynamics of each atom in the system, and Monte Carlo simulation, in which configurations of the system are generated via a Markov chain process that asymptotically are distributed according to the appropriate equilibrium probability. Properties of interest are then computed as averages over the configurations generated. Molecular simulation is a complex computational method with many intricacies involved in obtaining useful, reproducible results. Over the last decade, we have been developing the open-source Molecular Simulation Design Framework [(MoSDeF)](https://mosdef.orf "(MoSDeF)") that facilitates the development and execution of complex molecular simulations while making the simulations fully reproducible. Our efforts to develop MoSDeF are described in Section 3 below.

#### 1. Molecular Modeling of Systems Relevant to Capacitive Energy Storage Devices
Our research using molecular modeling to understand, and ultimately predict, the physical properties of systems relevant to capacitive energy storage devices is funded by the Department of Energy Office of Science through an [Engineering Frontier Research Center](https://www.energyfrontier.us "Energy Frontier Research Center") called the Fluid Interface Reactions Structures and Transport (or [FIRST](https://web.ornl.gov/sci/first/ "FIRST") Center.

Ionic liquids have been a major topic of research due to their high voltage windows, but suffer from slow transport properties (slow diffusion, high viscosity).  
To overcome this issue, ionic liquid and organic solvent solutions were [studied](https://pubs.acs.org/doi/abs/10.1021/acs.jpclett.6b02587) with QENS and MD, where it was believed that solvent polarity dictated the ion transport properties in these solutions.
As a follow-up computational screening over 400+ ionic liquid-solvent mixtures was conducted, where it was determined that solvent diffusion, not polarity, is the best indicator of ion transport.
Many of the trends predicted from the computational screening study were later confirmed through [NMR experiments](https://pubs.acs.org/doi/abs/10.1021/acs.jpcb.0c07582).

#### 2. Nanoscale Friction and Tribology
Micro- and nano-electromechanical (MEMS and NEMS) devices can be found in a wide range of applications, ranging from gyroscope and accelerometer, which are embeded in most smart devices, to biosensors and biochip. 
These devices, however, still have many design constraints, mainly due to their tribological issues. 
Because of their sizes, these devices have high surface-area-to-volume ratios, and hence are more susceptible wear and tear, as well as other surface forces usually negligible in larger system. 
Hence, developing a lubrication scheme is essential for these devices to reach their full potential.
This project utilize molecular dynamics simulation to investigate using thin film coatings as potential lubricants for such systems. 
Specifically, we perform high-throughput screening try to search for optimal thin film design. 
We also utilize machine learning algorithm to study the trends induced by each parameters of the thin film. 
Part of this study has been [published](https://pubs.acs.org/doi/abs/10.1021/acs.jctc.9b01183),  and we are still continuing working different aspect of this subject. 

#### 3. Open-Source Software Development - The Molecular Simulation Design Framework (MoSDeF)
The [Molecular Simulation and Design Framework (MoSDeF)](https://mosdef.org), is a suite of python libraries focusing on the initialization, parametrization, and enabling large-scale screening of chemical systems for molecular simulation.
These tools are completely open source, licensed under the [MIT License](https://opensource.org/licenses/MIT), and developed publicly at the MoSDeF GitHub organization [mosdef-hub](https://github.com/mosdef-hub).
The three main libraries that make up MoSDeF are:
  1. [mBuild](https://mbuild.mosdef.org): A hierarchical, modular system builder to generate starting configurations for molecular simulation.
  2. [foyer](https://foyer.mosdef.org): A package to assign interaction parameters for molecular systems, as well as a way to disseminate this interaction information.
  3. [gmso](https://gmso.mosdef.org): A flexible library to store chemical topology information for molecular simulations.
These tools are designed to be used together as well as separately, encouraging modular use depending on the user's use-case.

One of the goals of MoSDeF is to enable simulations to be published in such a way that they are reproducible. Reproducibility in scientific research has become a a forefront issue in science, and reproducibility is becoming increasingly expected of computational research. We have been promoting the concept of molecular simulations that are <b>T</b>ransparent, <b>R</b>eproducible, <b>U</b>sable by others, and <b>E</b>xtensible (TRUE). In the Thompson <i>et al.</i> [open access paper](https://www.tandfonline.com/doi/epub/10.1080/00268976.2020.1742938?needAccess=true "open access paper") cited below, we explore the concept of TRUE simulations as well as review MoSDeF capabilities at the time of the writing of the paper. For the most up-to-date information on MoSDeF, please visit [mosdef.org](https://mosdef.org "mosdef.org").

#### LIterature cited
<small>Thompson, M. W., Gilmer, J. B., Matsumoto, R. A., Quach, C. D., Shamaprasad, P., Yang, A. H., Iacovella, C. R., McCabe, C. & Cummings, P. T., "Towards molecular simulations that are transparent, reproducible, usable by others, and extensible (TRUE)," <i>Mol. Phys.</i> <b>118</b>, e1742938 (2020). DOI: 10.1080/00268976.2020.1742938<small>
