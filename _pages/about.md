---
permalink: /
title: "Welcome to my personal website!"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

## News

- December, 2022: Our paper _Bridging Hardware and Software Analysis with 2C: A Word-Level-Circuit-to-C Translator_ is accepted at [TACAS 2023](https://www.etaps.org/2023/conferences/).
- December, 2021: My dissertation wins the Lam Research Ph.D. Thesis Award at NTU.
- June, 2021: I become a member of the [Phi Tau Phi](http://www.phitauphi.org.tw/) scholastic honor society.

## Short Biography

I am a postdoctoral researcher affiliated with [Software and Computational Systems Lab](https://www.sosy-lab.org/) at LMU Munich, Germany.
I obtained a Ph.D. degree in Electronics Engineering from National Taiwan University in 2021.
My research directions are the analysis and optimization of computational systems, with a focus on applying formal methods.

I enjoy doing research and collaborating with people from different countries.
During my doctoral study,
I was a research intern at
[IBM T. J. Watson Research Center](https://www.research.ibm.com/labs/watson/) (July - October 2016),
an internship student at [National Institute of Informatics](https://www.nii.ac.jp/en/) (September 2018 - February 2019),
and a visiting student at [LMU Munich](https://www.lmu.de/en/) (September 2019 - August 2020).

If you want to know more about me, please take a look at my [CV](../files/Nian-Ze.Lee.CV.pdf).

## Recent Publications

The following are some of my recent publications.
For a complete list, please click the `Publications` button on the top menu.

### 2023

- [Bridging Hardware and Software Analysis with Btor2C: A Word-Level-Circuit-to-C Translator](https://www.sosy-lab.org/research/btor2c/Bridging_Hardware_and_Software_Analysis_with_Btor2C.pdf)
  - Translating word-level [Btor2](https://doi.org/10.1007/978-3-319-96145-3_32) circuits to C programs and applying software analysis
  - A [reproduction package](https://doi.org/10.5281/zenodo.7551707) for the conducted experiments
  - A supplementary [webpage](https://www.sosy-lab.org/research/btor2c/) for browsing the experimental results
  - To appear at [TACAS 2023](https://www.etaps.org/2023/conferences/)

### 2022

- [Interpolation and SAT-Based Model Checking Revisited: Adoption to Software Verification](https://arxiv.org/abs/2208.05046)
  - Adoption of [McMillan's 2003 algorithm for interpolation-based model checking](https://doi.org/10.1007/978-3-540-45069-6_1) to software verification
  - A [reproduction package](https://doi.org/10.5281/zenodo.6700515) for the conducted experiments
  - A supplementary [webpage](https://www.sosy-lab.org/research/cpa-imc/) for browsing the experimental results

### 2021

- [Stochastic Boolean satisfiability: Decision procedures, generalization, and applications, doctoral dissertation](http://dx.doi.org/10.6342%2fNTU202101397)
  - An [author copy](../files/Nian-Ze.Lee.Dissertation-secure.pdf) of the dissertation
  - A supplementary [reproduction package](https://doi.org/10.5281/zenodo.5084147) for the evaluation
- [Dependency stochastic Boolean satisfiability: A logical formalism for NEXPTIME decision problems with uncertainty, AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/16506)

### 2020

- [Constraint solving for synthesis and verification of threshold logic circuits, Trans. CAD](https://doi.org/10.1109/TCAD.2020.3015441)
- [Engineering change order for combinational and sequential design rectification, DATE](https://doi.org/10.23919/DATE48585.2020.9116504)
  - This work was in collaboration with Dr. Victor N. Kravets from IBM Research.

### 2019

- [Stability analysis for safety of automotive multi-product lines: A search-based approach, GECCO](https://doi.org/10.1145/3321707.3321755)
  - This work was in collaboration with Dr. Paolo Arcaini, Prof. Fuyuki Ishikawa from NII, and Dr. Shaukat Ali from Simula Research Laboratory.

## Software Projects

I am the primary maintainer of the following projects:

- [`Btor2C`](https://gitlab.com/sosy-lab/software/btor2c): a translator from the word-level modeling language Btor2 to the programming language C
- [`reSSAT` and `erSSAT`](https://github.com/NTU-ALComLab/ssatABC): solvers for the random-exist/exist-random quantified fragments of stochastic Boolean satisfiability
- [`ssat-benchmarks`](https://github.com/NTU-ALComLab/ssat-benchmarks): a collection of stochastic Boolean satisfiability formulas for benchmarking (**Contributions Welcome!**)
- [`TLCollapseVerify`](https://github.com/NTU-ALComLab/TLCollapseVerify): collapse operation and efficient verification of threshold logic in a synthesis/verification tool [`ABC`](https://github.com/berkeley-abc/abc)

I participate in the following projects:

- [`CPAchecker`](https://gitlab.com/sosy-lab/software/cpachecker): a configurable software-verification platform
  - I contribute to adopting McMillan's [interpolation-based model-checking algorithm](https://link.springer.com/chapter/10.1007/978-3-540-45069-6_1) to software.
- [`BenchExec`](https://github.com/sosy-lab/benchexec): a reliable and precise benchmarking framework
  - I contribute to incorporating SAT solver [Kissat](https://github.com/arminbiere/kissat) and ABC.

## Contact

My email address: nian-ze.lee@sosy.ifi.lmu.de

Please send me encrypted emails!

My [GPG key](https://keys.openpgp.org/vks/v1/by-fingerprint/6211DD38D7BD0167253BB4F8EBA3A3F7F4F9BBEC) can be downloaded from the Keys OpenPGP server.
Fingerprint: 6211 DD38 D7BD 0167 253B B4F8 EBA3 A3F7 F4F9 BBEC
