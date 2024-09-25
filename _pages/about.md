---
permalink: /
title: "Welcome to my personal website!"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

**I will join the EE department at NTU as Assistant Professor from February 2025!**

- Information for prospective students: [slides](files/2024-09-27-EDA-Recruiting-Nian-Ze.pdf)

**I am looking for prospective Ph.D. students to work on the verification of hardware and software systems.
The [project](https://gepris.dfg.de/gepris/projekt/536040111?language=en) is funded by the German Research Foundation (DFG). Please refer to the [slides](files/2024-04-07_COOP24_Bridging_Hardware_Software_Formal_Verification_Nian-Ze.pdf) for more information.**

## Short Biography

I am a postdoctoral researcher affiliated with [Software and Computational Systems Lab](https://www.sosy-lab.org/) at LMU Munich, Germany.
I obtained a Ph.D. degree in Electronics Engineering from National Taiwan University in 2021.
My research directions are the analysis and optimization of computing systems, with a focus on formal methods.

Here are my:

- [CV](../files/Nian-Ze.Lee.CV.pdf)
- [Publication list](../files/Nian-Ze.Lee.Publications.pdf)
- [Research statement](../files/Nian-Ze.Lee.Research-Statement.pdf)
- [Teaching experience](../files/Nian-Ze.Lee.Teaching.pdf)

## News

- 2024-07-15: Our [FSE 2024](https://conf.researchr.org/home/fse-2024) paper [_A transferability study of interpolation-based hardware model checking for software verification_](https://doi.org/10.1145/3660797) and its [reproduction package](https://doi.org/10.5281/zenodo.11070973) won the [ACM SIGSOFT Distinguished Paper Award](https://2024.esec-fse.org/info/awards#acm-sigsoft-distinguished-paper-award) and [Best Artifact Award](https://2024.esec-fse.org/info/awards#distinguished-artifacts).
- 2024-04-11: Our [TACAS 2024](https://www.etaps.org/2024/conferences/tacas/) paper [_Btor2-Cert: A certifying hardware-verification framework using software analyzers_](https://doi.org/10.1007/978-3-031-57256-2_7) won the **Distinguish Artifact Award** (cf. [reproduction package](https://doi.org/10.5281/zenodo.10548597)).
- 2024-04-10: Our [SPIN 2024](https://spin-web.github.io/SPIN2024/) paper [_Augmenting interpolation-based model checking with auxiliary invariants_](https://doi.org/10.48550/arXiv.2403.07821) won the **Best Paper Award**.
- 2024-03-28: Our grant proposal [_Bridging Hardware and Software Analysis_](https://gepris.dfg.de/gepris/projekt/536040111?language=en) was approved by the German Research Foundation (DFG)! See the [slides](files/2024-04-07_COOP24_Bridging_Hardware_Software_Formal_Verification_Nian-Ze.pdf) of my talk at [COOP 2024](https://coop.sosy-lab.org/2024/) for more details.
- 2023-12-05: Our verifier [CPV](https://gitlab.com/sosy-lab/software/cpv) ranks 6th (out of 26 tools) as a first-time participant in the category _ReachSafety_ at [SV-COMP 2024](https://sv-comp.sosy-lab.org/2024/).

## Software Projects

I am the primary designer and maintainer of the following projects:

- [`Btor2C`](https://gitlab.com/sosy-lab/software/btor2c): a translator from the word-level modeling language Btor2 to the programming language C
- [`Btor2-Cert`](https://gitlab.com/sosy-lab/software/btor2-cert): a certifying hardware verifier using software analyzers
- [`CPV`](https://gitlab.com/sosy-lab/software/cpv): a circuit-based program verifier
- [`MoXIchecker`](https://gitlab.com/sosy-lab/software/moxichecker): the first direct model checker for the modeling language [MoXI](https://doi.org/10.1007/978-3-031-65627-9_10)
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
