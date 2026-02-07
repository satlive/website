---
layout: post
title: "PhD: Beyond resolution (University of Lleida)"
shorttitle: PhD@Lleida
author: Carlos Ansótegui
tags: PhD Position
excerpt: CoRDS Doctoral Network is offering a PhD funding related to SAT. The deadline for applications will be extended.
deadline: 2026-01-06
link: https://www.cords-dn.at/phd-topics/
---

Host: University of Lleida; Academic partner: University College Cork; Industry partner: OMP

The Satisfiability (SAT) problem, the first problem shown to be NP-complete, asks whether a Boolean formula in Conjunctive Normal Form has a satisfying assignment and is fundamental to computer science. SAT solvers have improved dramatically over recent decades due to techniques such as non-chronological backtracking and conflict-driven clause learning (CDCL), allowing modern solvers to handle industrial instances with hundreds of thousands of variables and millions of clauses.

More powerful SAT solvers can also improve Maximum Satisfiability (MaxSAT), the optimization version of SAT, which seeks to satisfy as many clauses as possible while distinguishing between hard and soft constraints. SAT-based MaxSAT algorithms repeatedly invoke a SAT solver to test bounds on the optimum. This thesis conjectures that significant progress in core-guided MaxSAT solvers (a family of MaxSAT solvers) requires selecting effective core sequences rather than merely optimizing search within a fixed sequence. Different core sequences can lead to vastly different performance, including exponentially harder instances, making their avoidance essential. In this thesis, we aim to design meta-algorithms that efficiently explore and select favorable core sequences.

Finally, gadgets allow us to transform a SAT instance into a Max2SAT instance for use with MaxSAT solvers. The combination of such gadgets with MaxSAT algorithms can yield proof systems stronger than Resolution. In this thesis, we aim to build on these efforts by offering new insights into generating SAT-to-Max2SAT gadgets that can be exploited more efficiently by MaxSAT solvers.

To demonstrate impact beyond benchmarks, the project will apply these techniques to challenging mathematical and industrial problems.