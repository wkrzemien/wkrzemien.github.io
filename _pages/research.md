---
layout: archive
title: "Research Interests"
permalink: /research/
author_profile: true
---

My main interests are focused on novel imaging algorithms and their applications, machine learning techniques for noise reduction, and scientific software development. Last but not least, I am a curious physicist who wants to understand the rules governing the quantum world, engaged in (too many ;-)) fundamental research including tests of discrete symmetries and quantum entanglement.

---

### Fundamental Physics
---
* searches for discrete symmetry violations ([CPT](#anchor-discrete))
* quantum correlations in (relatively) high-energy photon systems ([QC](#anchor-quantum))
* mirror matter searches 
* searches for new type of nuclear matter 

### Methods ans applied studies:
---
* scientific software development
* industrial applications for PET imaging ([IMPET](#anchor-impet))
* novel image reconstruction algorithms for PET tomography 

## Fundamental Physics

<a name="anchor-discrete"></a>
### Discrete Symmetries

🟢 **Active** &nbsp;|&nbsp; **Collaborations:** [LHCb](https://lhcb-public.web.cern.ch/) (CERN), Previously: [J-PET](http://koza.if.uj.edu.pl/pet/), [KLOE-2](http://w3.lnf.infn.it/research/particle-physics/kloe-2/?lang=en)

My interests are focused on the experimental testing of discrete symmetries, which are related to fundamental questions in modern physics, e.g. the asymmetry of matter over antimatter, the basics of quantum mechanics (quantum oscillations, entanglement, and decoherence phenomena), and the validity of the fundamental CPT and Lorentz symmetries.

CPT symmetry - the combined invariance under charge conjugation, parity, and time reversal -  is one of the cornerstones of the Standard Model, thought to be exactly conserved by Nature. However, small CPT-violating (CPTV) effects are admissible in several theories beyond the Standard Model. One of the most sensitive methods to experimentally search for the CPTV effects is by studying the flavour mesons oscillations, approaching Planck-scale precision.

In our research published in Physics Review D, we set new limits on the CPTV parameters in charm meson oscillations by taking advantage of the world's largest dataset of D0 mesons collected by the LHCb collaboration. Our results provide the most stringent constraints on CPT symmetry violation in the charm sector - two orders of magnitude tighter than previous bounds. They were incorporated into the 2025 edition of the Particle Data Group review.  

limits on particle-antiparticle decay width difference for three neutral flavour meson families|  limits on particle-antiparticle mass difference in the charm sector
:----------------------:|:----------------------:
 ![](/images/cpt/dG_in_sectors-1.png) |![](/images/cpt/deltam-1.png)

→ [Physical Review D 110, 055021 (2024)](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.110.055021) &nbsp;|&nbsp; → [PDG 2025 entry](https://pdglive.lbl.gov/DataBlock.action?node=S032CPT)

---

<a name="anchor-quantum"></a>
### Quantum Correlations in High-Energy Photon Systems

🟢 **Active** &nbsp;| 

Quantum entanglement is typically studied in low-energy systems. Our work investigates whether polarization correlations between high-energy photon pairs — produced in particle-antiparticle annihilation — can serve as a sensitive probe of quantum mechanics at higher scales. This line of research bridges fundamental quantum mechanics and high-energy particle physics, asking whether the entanglement structure familiar from quantum optics survives and remains testable in the MeV photon regime. It can also have some applications in medical and industrial imaging.

I contributed to the theoretical framework and data analysis for two studies in this area.

![](/images/correlations/10052_85_10.png)

→ [Scientific Reports 14, 9672 (2024)](https://www.nature.com/articles/s41598-024-60472-1) &nbsp;|&nbsp; → [Eur. Phys. J. C 85, 1115 (2025)](https://link.springer.com/content/pdf/10.1140/epjc/s10052-025-14862-y)


---

### Search for Eta Mesic Nuclei (WASA-at-COSY, COSY-11)

⚫ **Completed** &nbsp;|&nbsp; **Role:** PhD thesis and first postdoc &nbsp;|

My doctoral work, carried out partly at Forschungszentrum Jülich (Germany), focused on the search for a new form of nuclear matter: eta mesic nuclei, bound states in which an eta meson is captured inside an atomic nucleus. Their existence would provide direct insight into the eta-nucleon interaction and the structure of the N*(1535) resonance. The analyses were performed within the WASA-at-COSY collaboration. The first article published in PRC is based on my PhD thesis dedicated to searches for eta-mesic helium. The second one, published in NPA, is based on the analysis done together with Magdalena Skurzok.

→ [Phys. Rev. C 87, 035204 (2013)](https://journals.aps.org/prc/abstract/10.1103/PhysRevC.87.035204) &nbsp;|&nbsp; → [Nucl. Phys. A 959, 102 (2017)](https://www.sciencedirect.com/science/article/pii/S0375947417300064)

---

## Applied Imaging & PET Tomography

<a name="anchor-impet"></a>
### IMPET — Industrial Multiphoton PET Tomography

🟢 **Active** &nbsp;|&nbsp; **Role:** PI &nbsp;|&nbsp; Foundation for Polish Science, First Team FENG &nbsp;|&nbsp; Budget: ~940K EUR

IMPET introduces a novel approach to industrial imaging by combining multiphoton PET technology with quantum decoherence modelling. Where conventional two-gamma PET uses a single pair of annihilation photons, multiphoton detection captures richer event information. A distinctive feature of the project is the use of quantum correlation properties of the photon system as a complementary source of information about material properties, going beyond what spatial distributions alone can provide.

The project targets two concrete industrial applications. The first is **dynamic flow imaging** in granular systems and opaque fluids — such as liquid metals used in the cooling of nuclear reactors or high-performance electronics — environments inaccessible to optical methods. The second is **3D imaging of porous materials**, including membranes used in seawater desalination and renewable energy systems, enabling precise quantification and localisation of pore sizes and structural defects.

On the methodology side, AI-based correction and noise reduction techniques will be integrated early in the data processing pipeline, and an enhanced Positron Emission Particle Tracking (PEPT) method is planned, capable of simultaneously tracking a large number of radiotracers. Scanner performance will be evaluated through advanced Monte Carlo simulations.

The project is conducted in scientific collaboration with [Beatrix Hiesmayr](https://it-u.at/en/research/professors/beatrix-c-hiesmayr/) (IT:U and University of Vienna), a leading expert in quantum information and entanglement, and [David Sarrut](https://dsarrut.github.io) (Laboratoire CREATIS, Lyon), a key developer of the GATE simulation package. Industrial partnership with [Creotech Instruments S.A.](https://creotech.pl/) supports the development of a cost-effective scanner design targeting both scientific and industrial research environments.

![](/images/impet/post1-min.png)
→ [IMPET project website](https://pet.ncbj.gov.pl/)

---

### MC modelling & Image Reco development

🟢 **Active** &nbsp;|&nbsp; **Role:** Developer and Scientist &nbsp;|

I contributed to the assessment of total-body scanners, the development of novel PET methods and tools  including positronium MC modelling.
Also I participated in studies of  possible improvement in positional resolution by incorporating prompt gamma detection
, and the application of machine learning for noise reduction and signal enhancement.

→ [Computer Science 26(SI) (2025)](https://journals.agh.edu.pl/csci/article/view/7057)

---

<a name="anchor-tbs"></a>
### PET Image Reconstruction Software and detector optimization studies

⚫ **Completed** &nbsp;|&nbsp; **Role:** Group leader, Total Body Software (J-PET) &nbsp;|&nbsp; **2019–2024**

I led the Total Body Software group within the J-PET collaboration, responsible for developing medical data processing and image reconstruction software for next-generation cost-effective total-body polymer PET scanners. The work covered image reconstruction algorithms, image correction methods, Monte Carlo simulations of scanner geometry.

A key study optimised total-body J-PET geometry for both two-gamma and multi-gamma tomography using Monte Carlo simulations. 

:----------------------:|:----------------------:
 ![](/images/total_geometry/Fig2-1-1.jpeg) |![](/images/total_geometry/Fig2bis-1-1.jpeg)

 ![](/images/total_geometry/Fig10_update-1.jpeg) 

→ [Medical Physics (2024)](https://onlinelibrary.wiley.com/share/author/TIMWB9IG3TXSQWSUDANR?target=10.1002/mp.17627) &nbsp;|

---

## Other projects:
---
* Application of Convolutional Neural Networks for LHCb electromagnetic calorimeter cluster reconstruction (see [here](https://pubs.aip.org/aip/acp/article/3061/1/040002/3275598/Machine-learning-solutions-for-cluster))


## Service & Coordination Roles

**OpenGate Steering Committee**  🟢 — member since 2019.

**EuroHPC PL** ⚫ — NCBJ coordinator of the National Supercomputing Infrastructure project (2021–2023), part of the European initiative to make Europe a world leader in supercomputing. Within this role I led the NCBJ contribution: a software platform for quantum simulations and medical imaging, encompassing (1) Monte Carlo simulation tools for tracking the evolution of quantum correlations in photon systems emitted from patients' bodies, (2) novel image reconstruction algorithms for multiphoton tomography,  and (3) a service for generating realistic total-body scanner training data using Generative Adversarial Networks — addressing the chronic scarcity of labelled data for deep learning in medical imaging. → [EuroHPC PL project](https://www.ncbj.gov.pl/en/projekt/eurohpc-pl-national-supercomputing-infrastructure-eurohpc)
![](/images/eurohpc/platform_v2-1-min.jpeg)

**J-PET Analysis Framework** ⚫ — initiator and long-term leader of the open-source data analysis platform for the J-PET project. See the [Software](/software/) page for details.

**DIRAC** ⚫ — earlier, I contributed to the development of the Message Queue architecture (RabbitMQ, ActiveMQ) and Pilot Loggers within the [DIRAC](https://github.com/DIRACGrid/DIRAC) distributed computing framework, used by LHCb and several other large scientific experiments. Full details on the [Software](/software/) page.
