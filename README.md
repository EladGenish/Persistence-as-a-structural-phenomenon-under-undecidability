Admissibility, Persistence, and Anti-Closure
A Formal Framework with Computational Realizability

This repository contains the publish-ready preprint accompanying a formal framework for persistence, continuation, and self-referential dynamics under admissibility constraints.

The work develops an axiomatic structure in which persistence arises without objectives, optimization, or predefined representations, and shows how incompleteness and non-closure act as generative pressure rather than failure modes.

A concrete computational realization (RNSE) is discussed only as an existence proof of realizability; the theoretical results do not depend on any specific implementation.

Overview

The paper introduces a unified framework that:

Defines admissibility-based continuation as the primitive driver of system evolution

Recasts “fine-tuning” as viability bands under survivability constraints

Treats incompleteness and anti-closure as necessary conditions for persistence

Separates imported classical results (e.g. Gödel) from novel contributions

Provides a falsifiable, scoped, physics-facing layer (CLD) with explicit limits

Demonstrates computational realizability via a non-optimizing substrate (RNSE)

All major claims are clearly labeled, proof-status honest, and explicitly scoped.

Contents

paper_publish_ready_v3.pdf
The complete, publish-ready preprint

paper_publish_ready_v3.tex
LaTeX source (clean build, labeled results, scoped claims)

Key Contributions

A formal admissibility structure governing continuation and persistence

A survivability-based interpretation of apparent fine-tuning

A principled link between self-reference, anti-closure, and cyclic dynamics

A clear separation between theory, imported results, and predictions

An explicit falsification checklist defining what would count as failure

Computational Realizability

The framework is not purely abstract.
The paper shows that the admissibility and continuation structure can be realized by an executable system in which:

Continuations are proposed and filtered by coherence constraints

Persistence and cycles are consequences, not objectives

Observables are read-only and do not drive evolution

No implementation details are disclosed in this repository.

Scope and Limits

This work does not claim:

a completed physical theory

empirical validation of CLD predictions

uniqueness of implementation

It does claim:

internal formal coherence

computational realizability in principle

falsifiability of its physics-facing predictions

Status

Preprint

Proof-status honest (proofs, proof sketches, or explicit downgrades provided)


The testable signatures described in Section 8.2 (boundary-leading pulse, phase-lag maps, non-objective compression, boundary sensitivity) have been computationally validated through extensive testing over 2025-2026. Results and visualisations from these experiments have been shared on my public research channels, including ablation studies, critical-line analysis, spatial structure emergence, and cross-run learning demonstrations.

The full technical implementation of RNSE—including operator specifications, grid architecture, and parameter optimisation—remains proprietary as I work toward commercial deployment. The framework formalised in this paper establishes the theoretical foundations and falsification criteria; interested parties are welcome to reach out regarding partnerships, licensing, or investment opportunities.

This approach protects the novel computational architecture while ensuring the conceptual contributions are publicly timestamped and independently verifiable.
Suitable for public discussion, critique, and review

Citation

If you reference this work, please cite the preprint directly.
A BibTeX entry is provided in the paper.
