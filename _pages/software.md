---
permalink: /software/
title: "Software"
gallery:
  - url: software/api_scheme.png
    image_path: software/api_scheme.png
    alt: "J-PET Framework API"
    title: "J-PET Framework API"
---

I like coding :-) and I was lucky enough to find a lot of opportunities to join my research activities with programming tasks.
I have been involved in various scientific projects which included the development of open-source programs. I use mostly C++ and Python.

---
# J-PET Framework

{% include gallery %}

[Github repository of the Framework](https://github.com/wkrzemien/j-pet-framework)


I was the initiator and for years the leader of the team that has been developing an open-source data analysis software platform  
for the [J-PET](http://koza.if.uj.edu.pl/pet/) project, in the frame of which we built a novel positron emission tomography scanner that turned out to be a perfect tool for
precise physics tests of the fundamental properties of Nature.

The latest article describing the J-PET Framework can be found [here](https://www.sciencedirect.com/science/article/pii/S2352711020300509?via%3Dihub)
One can find the list of publications [here](http://koza.if.uj.edu.pl/publications/pet), including our recent Nature Communication [article](https://www.nature.com/articles/s41467-021-25905-9).

J-PET Framework provides a common environment for implementation of reconstruction, calibration, and filtering procedures, as well as for user-level analyses of Positron Emission Tomography data. 
The library contains a set of building blocks that can be combined by users with even little programming experience, into chains of processing tasks through a simple API.
The J-PET environment can be used to e.g. develop a reconstruction chain for the real data collected by a PET scanner or to implement a calibration procedure, an image reconstruction method, or any kind of a multi-step analysis. Other typical applications consist of comparative studies of prototype PET scanner performance based on the Monte Carlo (MC) simulations.
The Framework software platform is currently used by scientists from the Jagiellonian University in Kraków, National Centre for Nuclear Research in Warsaw and INFN Laboratori Nazionali di Frascati and has been successfully deployed on different scales starting from laptops and personal PC-s, through mid-size computing clusters to HPC Swierk cluster.
Currently, use cases of the J-PET Framework span among various data analyses and imaging applications of the first J-PET device. Virtually, any studies involving data analysis within the J-PET project are based on the
J-PET Framework. 

 
---
# DIRAC

![](/images/software/DIRAC-logo.png)

[DIRAC](https://github.com/DIRACGrid/DIRAC) is an interware, meaning a software framework for distributed computing written in Python.
DIRAC is used by several scientific projects, including large particle experiments, such as LHCb, Belle-II, ILC, CTA, BES-3  and others.
DIRAC builds a layer between the users and the resources offering a common interface to a number of heterogeneous providers, integrating them in a seamless manner, providing interoperability, at the same time as an optimized, transparent and reliable usage of the resources.

In the frame of the LHCb project, I participated in the development and implementation of the Message Queue architecture (RabbitMQ, ActiveMQ) and the development of the so-called Pilot Loggers as a part of the  DIRAC echo-system.

More on the Message Queue implementation in DIRAC can be found [here](https://www.epj-conferences.org/articles/epjconf/pdf/2019/19/epjconf_chep2018_03018.pdf). Some information on the concept of the distributed agents
called Pilots is given [here](https://iopscience.iop.org/article/10.1088/1742-6596/898/9/092024).

---
# Other staff 

Currently, I am involved in the exploratory project of Convolutional Neural Networks application for the LHCb Electromagnetic Calorimeter (ECAL) clusterization algorithm.
In the past, I coordinated the software activities of the NCBJ group dedicated to the upgrade of the reconstruction algorithms for ECAL. I also participated in the refactorization and parallellization
of the old LHCb software for ECAL.  



