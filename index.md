---
layout: default
permalink: /
nav_order: 1
title: SAMCO Home
---

# SAMCO (Surrogate-Assisted Multi-Criteria Optimization) #
---

Welcome to the web page of the SAMCO Lorentz Center workshop. SAMCO stands for Surrogate-Assisted Multi-Criteria Optimization. The SAMCO workshop took place from February 29, 2016 till March 4, 2016 at the [Lorentz Center](http://www.lorentzcenter.nl/) in Leiden, The Netherlands.

Note that this webpage is a reconstruction of the original webpage, hosted at Inria's GForge.

For details on the program and the links to the talks' slides, see the [Schedule](schedule).

## Background ##
In many optimization tasks, different conflicting aims, such as quality and cost, need to be considered. Due to changing customer groups and needs, in most cases no a priori preference information is available. Hence, we are interested in finding a set of solutions that reflects the optimal trade-offs among the conflicting optimization criteria. This kind of problem, we call a (set-based) multi-criteria optimization (MCO) problem.

Beginning with the seminal Efficient Global Optimization paper of Jones et al. in 1998, sequential surrogate-assisted optimizers became accepted for solving problems with expensive black box objective functions. In those sequential approaches, the surrogate model estimates the response surface of the problem by means of an initial experimental design. This surrogate model allows the next solution to be selected for evaluation based on a suitable figure of merit.

## Objectives of the Workshop ##
With our SAMCO workshop, we aim(ed) at bridging the research in both topics, set-based multi-criteria optimization and surrogate-assisted optimization. The intersection of these topics is an emerging research area, but work in the field is still very heterogeneous and distributed over different countries and faculties. Therefore, our workshop brings together researchers from all backgrounds and allows new concepts connected to SAMCO to be discussed under a holistic perspective. In particular, we plan(ned) five key aspects of SAMCO to be addressed:

* Overview of existing libraries and approaches
* Beyond one model per objective function: higher-level surrogate approaches
* Ensembles of surrogate models
* Benchmarking
* Theoretical aspects

For slightly more details on background and objectives of the workshop, see this [synopsis in pdf format](samco-synopsis-web.pdf).

## Organization ##
The SAMCO workshop was organized by

* Dimo Brockhoff, Inria Lille - Nord Europe, France
* Michael Emmerich, Leiden University, The Netherlands
* Boris Naujoks, TH Köln, Germany
* Tobias Wagner, TU Dortmund University, Germany

at the Lorentz-Center@Oort. <!--The official web page from the Lorentz Center can be found here.-->

## Subgroups ##
Subgroups with own pages:

* [Libraries and approaches](libraries)
* Noise and uncertainty
* [Benchmarking](benchmarking)
* Exception handling
* Beyond



<link rel="stylesheet" href="{{ '/assets/css/custom.css' | relative_url }}"/>
