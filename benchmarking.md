---
layout: default
permalink: /benchmarking/
nav_order: 5
title: SAMCO - Benchmarking
---

# Subgroup "Benchmarking"  #
---

Participants: Dimo Brockhoff, Daniel Horn, Joshua Knowles, Ilya Loshchilov, Tea Tusar, Ivan Voutchkov

Besides discussions on how to extend the BBOB platform towards problems of interest for surrogate-assisted multi-objective algorithms, we started in particular to collect real-world benchmark functions that are available to the public and simulators that can be used to create such functions. If you are aware of other publicly available real-world benchmarks or free simulators not listed here, please let us know.

<!-- Make tables sortable -->
<script type="text/javascript" src="{{site.baseurl}}/sort-table.js"></script>

Note that, to sort the tables below, you can click on the table header of the corresponding column.



## Publicly available real-world optimization problems ##

{:.js-sort-table}
| Name                                                                                    |                   Authors                             | Domain                                                                             | # cont. variables | # int. variables | # bin. variables |   # constraints   | # obj. | license               | language    |
|-----------------------------------------------------------------------------------------|-------------------------------------------------------|------------------------------------------------------------------------------------|------------------:|-----------------:|-----------------:|:-----------------:|-------:|-----------------------|-------------|
| [HBV Rainfall-Runoff Model](http://jdherman.github.io/awr-hbv-benchmark/)	              | J. Kollat, J. Herman, P. Reed et al.	              | water resource management                                                          |                14 |                0 |                0 |         0         |      4 | LGPL                  | Java/C++    |
| [LRGV Water Portfolio Planning Benchmark](https://github.com/jrkasprzyk/LRGV)           | J. Kasprzyk, P. Reed, B. Kirsch, G. Characklis et al. | water resource management                                                          |               1-8 |                0 |                0 |         4         |     11 | LGPL                  | C++         |
| [HBV Rainfall-Runoff Model](https://github.com/jdherman/hbv/)	                          | M. Giuliani, J. Kollat, J. Herman et al.              | simulation calibration (water resource management)                                 |                12 |                0 |                0 | bound constraints |      2 | LGPL                  | Java/C++    |
| [Radar waveform optimization](http://homepage.ntlworld.com/evan.hughes1/)               | E. Hughes                                             | design optimization                                                                |                8+ |                0 |                0 |         1         |      9 | free for academic use | Matlab      |
| [Cassini 1](http://www.esa.int/gsp/ACT/inf/projects/gtop/cassini1.html)*                | D. Izzo	                                              | global trajectory optimization (multi gravity assist)                              |                 6 |                0 |                0 |         4         |      2 | GPL                   | C++, Python |
| [MGA-1DSM (TOF encoding)](http://www.esa.int/gsp/ACT/inf/projects/gtop/mga1dsm.html)    | D. Izzo                                               | global trajectory optimization (multi gravity assist with one deep space maneuver) |                18 |                0 |                0 |         0         |      2 | GPL                   | C++, Python |
| [MGA-1DSM (alpha encoding)](http://www.esa.int/gsp/ACT/inf/projects/gtop/mga1dsm.html)  | D. Izzo                                               | global trajectory optimization (multi gravity assist with one deep space maneuver) |                18 |                0 |                0 |         0         |      2 | GPL                   | C++, Python |
| GC-MS                                                                                   | J. Knowles                                            | ?                                                                                  |                 9 |                0 |                0 |         ?         |      9 |  ?                    | ?           |
| Airfoil redesign                                                                        | B. Naujoks                                            | design optimization                                                                |                18 |                0 |                0 |         0         |      2 |  ?                    | ?           |
| Airfoil drag min                                                                        | B. Naujoks                                            | design optimization                                                                |                 9 |                0 |                0 |         0         |      3 |  ?                    | ?           |
| Hospital assignment                                                                     | ?                                                     | ?                                                                                  |                 ? |                ? |                ? |         3         |      2 |  ?                    | ?           |
| SVN opt                                                                                 | D. Horn                                               | SVN accuracy vs. training time opt                                                 |               2-4 |                0 |                0 |         0         |      2 |  ?                    | ?           |
| Top trumps                                                                              | V. Volz                                               | balancing objectives for game                                                      |             K x L |            K x L |                ? |         0         |      2 |  ?                    | R           |

* Considered to be solved as a single-objective problem.

## Free simulators ##

| Name                                                                                    |                   Authors                                                                                                       | Domain                                                                             | # cont. variables | # int. variables | # bin. variables |   # constraints   | # obj. | license               | language                                 |
|-----------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------|------------------:|-----------------:|-----------------:|:-----------------:|-------:|-----------------------|------------------------------------------|
| XFoil	                                                                                  | M. Drela (also H. Youngren)	                                                                                                    | airfoil design                                                                     |                 ? |               ?  |               ?  |                ?  |      ? | GPL                   | C/Fortran 77, support for Win32 and Unix |
| EPANET (software that models water distribution piping systems)                         | US Environmental Protection Agency                                                                                              | water distribution                                                                 |                 ? |               ?  |               ?  |                ?  |      ? | none (public domain)  | DLL (Windows)                            |
| MATSim (multi-agent traffic flow simulation)                                            | TU Berlin, ETH Zurich and Senozon                                                                                               | transport                                                                          |                 ? |               ?  |               ?  |                ?  |      ? | GPL                   | Java                                     |
| ns-3 (discrete-event network simulator for Internet systems)                            | National Science Foundation, INRIA, Georgia Institute of Technology, University of Washington and U.S. Army Research Laboratory | networks                                                                           |                 ? |               ?  |               ?  |                ?  |      ? | GPL                   | Java                                     |





<link rel="stylesheet" href="{{ '/assets/css/custom.css' | relative_url }}"/>
