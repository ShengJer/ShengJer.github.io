---
title: "Canonical-Ensemble SCFT Derivation for an Linear Incompressible AB Diblock Melt (Density Explicit Formalism)"
date: 2026-02-25
permalink: /posts/2026/02/scft-canonical-derivation-ab-linear-diblock-melt-de/
categories:
  - polymer-field-theory
tags:
  - scft
  - diblock-copolymer
  - derivation
---

{% assign pdf_path = '/files/Research_Block_Posts/Polymer_Field_Theory/SCFT_derivation_density_explicit_diblock_linear.pdf' | relative_url %}

## Summary

This note summarizes a canonical-ensemble self-consistent field theory (SCFT) derivation for an linear incompressible AB diblock copolymer melt.

The derivation starts from a microscopic polymer model with:
- Gaussian-chain model
- Flory-Huggins A-B contact interaction
- A incompressibility constraint

It then introduces collective density fields and auxiliary conjugate fields through functional delta identities and Fourier representations. This converts the many-chain partition function into a field-theoretic form and defines an effective Hamiltonian.

At the mean-field saddle point, the SCFT equations are obtained, including:
- Forward/backward chain propagator equations
- Segment-density expressions from propagators
- Incompressibility condition
- Self-consistent relations between fields and densities

Finally, the derivation is recast into the common real-field and volume-fraction form, and interpreted through the free-energy decomposition into:
- Interaction enthalpy
- Field-coupling/incompressibility contribution
- Conformational entropy contribution

## Full Derivation (PDF)

The full derivation with complete equations is provided below.

- [Download the full derivation (PDF)]({{ pdf_path }})

## References

- Sides SW, Fredrickson GH. Parallel algorithm for numerical self-consistent field theory simulations of block copolymer structure. Polymer. 2003 Sep 1;44(19):5859-66.
- Gadelrab KR. Block copolymer self-assembly-a computational approach towards novel morphologies (Doctoral dissertation, Massachusetts Institute of Technology).

<iframe src="{{ pdf_path }}" width="100%" height="900" style="border: 1px solid #ddd; border-radius: 6px;" title="SCFT Derivation PDF"></iframe>

If the embedded viewer does not load in your browser, use the download link above.
