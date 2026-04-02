---
title: "Second Correlation Function of an Ideal Non-Interacting Gaussian Chain"
date: 2026-04-02
permalink: /posts/2026/04/ideal-gaussian-chain-second-correlation/
categories:
  - polymer-field-theory
tags:
  - polymer-statistics
  - gaussian-chain
  - correlation-function
  - derivation
---

{% assign pdf_path = '/files/Research_Block_Posts/Polymer_Field_Theory/ideal_non_interacting_Gaussian_chain_second_correlation.pdf' | relative_url %}

## Summary

This note derives the two-point correlation function of an ideal, non-interacting Gaussian chain in a step-by-step way.

It begins with a discrete Gaussian-chain model with independent bond vectors and defines the segment-pair correlation between monomers \(i\) and \(j\). The derivation then rewrites the delta functions in Fourier space, changes variables from monomer positions to bond vectors, integrates out the reference position, and reduces the remaining expression to Gaussian bond integrals.

The result shows that the relative separation between two chain segments is itself described by a Gaussian connector distribution whose width is set by the contour distance between those segments. Using this kernel as the basic building block, the note then constructs second correlation functions for diblock-chain densities, including both same-species correlations and the \(A\)-\(B\) cross-correlation.

Finally, the derivation takes the long-chain continuum limit and gives the correlation functions in both real space and Fourier space, ending with a compact dimensionless form for the \(A\)-\(B\) correlation kernel. These results are standard ingredients for random phase approximation analysis and polymer field theory.

## Full Derivation (PDF)

The full derivation with complete equations is provided below.

- [Download the full derivation (PDF)]({{ pdf_path }})

## References

- Dawson S. Ginzburg-Landau theory of complex spherical packing phases in soft condensed matter [dissertation].

<iframe src="{{ pdf_path }}" width="100%" height="900" style="border: 1px solid #ddd; border-radius: 6px;" title="Ideal Non-Interacting Gaussian Chain Second Correlation PDF"></iframe>

If the embedded viewer does not load in your browser, use the download link above.
