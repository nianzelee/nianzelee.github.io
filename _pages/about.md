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

- 2024-03-28: Our grant proposal is approved by the German Research Foundation (DFG)!
  We are hiring a Ph.D. student to work on [bridging hardware and software formal verification](files/2024-04-07_COOP24_Bridging_Hardware_Software_Formal_Verification_Nian-Ze.pdf).
- 2024-02-27: Our paper _Augmenting interpolation-based model checking with auxiliary
  invariants_ is accepted at [SPIN 2024](https://spin-web.github.io/SPIN2024/).
- 2023-12-22: Our paper _Btor2-Cert: A certifying
  hardware-verification framework using software analyzers_ is accepted at [TACAS 2024](https://www.etaps.org/2024/conferences/tacas/).
- 2023-12-05: Our verifier [CPV](https://gitlab.com/sosy-lab/software/cpv) ranks 6th (out of 26 tools) as a first-time participant in the category _ReachSafety_ at [SV-COMP 2024](https://sv-comp.sosy-lab.org/2024/).
- 2023-09-11: I organized the [8th International Workshop on CPAchecker](https://cpa.sosy-lab.org/2023/).
- 2023-09-04: I mentored a [project](https://www.sosy-lab.org/gsoc/gsoc2023.php) in the [Google Summer of Code 2023](https://summerofcode.withgoogle.com/).
- 2023-07-06: Our paper [_Interpolation and SAT-based model checking revisited: Adoption to software verification_](https://doi.org/10.48550/arXiv.2208.05046) is accepted by [_Journal of Automated Reasoning_](https://www.springer.com/journal/10817).
- 2023-07-06: Our paper [_CPA-DF: A tool for configurable interval analysis to boost program verification_](https://doi.org/10.1109/ASE56229.2023.00213) is accepted at [ASE 2023](https://conf.researchr.org/home/ase-2023).

## Short Biography

**I am on the academic job market!
Here are my [CV](../files/Nian-Ze.Lee.CV.pdf) and [publication list](../files/Nian-Ze.Lee.Publications.pdf).**

I am a postdoctoral researcher affiliated with [Software and Computational Systems Lab](https://www.sosy-lab.org/) at LMU Munich, Germany.
I obtained a Ph.D. degree in Electronics Engineering from National Taiwan University in 2021.
My research directions are the analysis and optimization of computing systems, with a focus on formal methods.

I enjoy doing research and collaborating with people from different countries.
During my doctoral study, I was

- a visiting student on DAAD scholarship at [LMU Munich](https://www.lmu.de/en/), Germany (September 2019 - August 2020),
- an internship student at [National Institute of Informatics](https://www.nii.ac.jp/en/), Tokyo, Japan (September 2018 - February 2019), and
- a research intern at [IBM T. J. Watson Research Center](https://www.research.ibm.com/labs/watson/), New York, U.S.A. (July - October 2016).

## Recent Publications

The following are some of my recent publications.
Please refer to my [publication list](../files/Nian-Ze.Lee.Publications.pdf)
or click the `Publications` button on the top menu for the complete list.

### 2023

- [Bridging hardware and software analysis with Btor2C: A word-level-circuit-to-C translator](https://doi.org/10.1007/978-3-031-30820-8_12) (TACAS)
  - Translating word-level [Btor2](https://doi.org/10.1007/978-3-319-96145-3_32) circuits to C programs and applying software analysis
  - A supplementary [webpage](https://www.sosy-lab.org/research/btor2c/) for an author copy of the paper and for browsing the experimental results
  - A [reproduction package](https://doi.org/10.5281/zenodo.7551707) for the conducted experiments

### 2022

- [Interpolation and SAT-based model checking revisited: Adoption to software verification](https://arxiv.org/abs/2208.05046)
  - Adoption of [McMillan's 2003 algorithm for interpolation-based model checking](https://doi.org/10.1007/978-3-540-45069-6_1) to software verification
  - A supplementary [webpage](https://www.sosy-lab.org/research/cpa-imc/) for browsing the experimental results
  - A [reproduction package](https://doi.org/10.5281/zenodo.6700515) for the conducted experiments

### 2021

- [Stochastic Boolean satisfiability: Decision procedures, generalization, and applications](http://dx.doi.org/10.6342%2fNTU202101397) (Doctoral dissertation)
  - An [author copy](../files/Nian-Ze.Lee.Dissertation-secure.pdf) of the dissertation
  - A supplementary [reproduction package](https://doi.org/10.5281/zenodo.5084147) for the evaluation
- [Dependency stochastic Boolean satisfiability: A logical formalism for NEXPTIME decision problems with uncertainty](https://doi.org/10.1609/aaai.v35i5.16506) (AAAI)

### 2020

- [Constraint solving for synthesis and verification of threshold logic circuits](https://doi.org/10.1109/TCAD.2020.3015441) (IEEE Trans. CAD)
- [Engineering change order for combinational and sequential design rectification](https://doi.org/10.23919/DATE48585.2020.9116504) (DATE)
  - Collaboration with Dr. Victor N. Kravets from IBM Research

### 2019

- [Stability analysis for safety of automotive multi-product lines: A search-based approach](https://doi.org/10.1145/3321707.3321755) (GECCO)
  - Collaboration with Dr. Paolo Arcaini and Prof. Fuyuki Ishikawa from NII, and Dr. Shaukat Ali from Simula Research Laboratory

## Software Projects

I am the primary designer and maintainer of the following projects:

- [`Btor2C`](https://gitlab.com/sosy-lab/software/btor2c): a translator from the word-level modeling language Btor2 to the programming language C
- [`Btor2-Cert`](https://gitlab.com/sosy-lab/software/btor2-cert): a certifying hardware verifier using software analyzers
- [`CPV`](https://gitlab.com/sosy-lab/software/cpv): a circuit-based program verifier
- [`reSSAT`, `erSSAT`](https://github.com/NTU-ALComLab/ssatABC): solvers for the random-exist and exist-random quantified fragments of stochastic Boolean satisfiability
- [`ssat-benchmarks`](https://github.com/NTU-ALComLab/ssat-benchmarks): a collection of stochastic Boolean satisfiability formulas for benchmarking (**Contributions Welcome!**)
- [`TLCollapseVerify`](https://github.com/NTU-ALComLab/TLCollapseVerify): collapse operation and efficient verification of threshold logic in a synthesis/verification tool [`ABC`](https://github.com/berkeley-abc/abc)

I participate in the following projects:

- [`CPAchecker`](https://gitlab.com/sosy-lab/software/cpachecker): a configurable software-verification platform
  - Design and implementation of McMillan's [interpolation-based model-checking algorithm](https://link.springer.com/chapter/10.1007/978-3-540-45069-6_1)
- [`BenchExec`](https://github.com/sosy-lab/benchexec): a reliable and precise benchmarking framework
  - Incorporation SAT solver [Kissat](https://github.com/arminbiere/kissat) and [ABC](https://github.com/berkeley-abc/abc)

## Contact

My email address: nian-ze.lee@sosy.ifi.lmu.de

Please send me encrypted emails!

My [GPG key](https://keys.openpgp.org/vks/v1/by-fingerprint/6211DD38D7BD0167253BB4F8EBA3A3F7F4F9BBEC) can be downloaded from the Keys OpenPGP server.
Fingerprint: 6211 DD38 D7BD 0167 253B B4F8 EBA3 A3F7 F4F9 BBEC
