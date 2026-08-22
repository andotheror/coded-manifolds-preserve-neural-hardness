# Coded Manifolds Preserve Neural Hardness at Critical Reach

## Abstract

Does sufficiently low curvature make neural networks easy to learn under the manifold hypothesis? Recent work nearly identified a sharp geometric boundary. It proved exponential hardness on manifolds of reach $O(n^\alpha)$ for every $\alpha<1/2$, while reach $\omega(\sqrt n)$ forces polynomial intrinsic volume and permits interpolation. The critical regime $\Theta(\sqrt n)$ was left open.

We close this boundary on the hard side. For every large ambient dimension $n$, we construct a connected closed $C^\infty$ curve in $[0,1]^n$ with reach $\Theta(\sqrt n)$ and a full-support, polynomial-time samplable distribution whose density is within constant factors of arclength. Learning linear-width one-hidden-layer ReLU networks on this distribution from noise-free labels requires $\tau^2\exp(\Omega(n))$ full statistical queries of tolerance $\tau$. Under polynomial-modulus Learning with Rounding, no polynomial-time learner exists even with arbitrary output hypotheses.

The construction replaces coordinate repetition by coding. We traverse a reflected Gray code of $\mathbb F_2^m$, embed its messages with an explicit systematic small-bias code, and smoothly round the resulting polygon. Character orthogonality gives a restricted isometry for every sparse signed measure needed by a chord and tangent. Federer's tangent formula then amplifies constant abstract reach to $\Omega(\sqrt n)$. The systematic coordinates preserve a linear Boolean prefix on all but an exponentially small fraction of local pieces, which yields an almost pairwise-independent family of continuous parity networks. This shows that the $\sqrt n$ threshold is a genuine critical point rather than a limitation of the previous construction.

## Contributions

- We answer the critical-reach question of: exponential learning hardness persists at reach $\Theta(\sqrt n)$.
- We introduce a small-bias character isometry for constant-sparse signed measures on the Boolean cube and a reach-transfer lemma for sparse smooth curves.
- We obtain $\tau^2\exp(\Omega(n))$ noise-free lower bounds for the full SQ model, not only correlational SQ, for linear-width one-hidden-layer ReLU networks.
- The hard input law has full support and density comparable to arclength, and it can be sampled to arbitrary precision in polynomial time.
- Under polynomial-modulus Learning with Rounding, the same geometry is hard for every polynomial-time learner of polynomial-size one-hidden-layer ReLU networks.

## Keywords

coded, manifolds, preserve, neural, hardness, critical, reach, does, sufficiently

## Files

- `main.pdf`
- `main.tex`
- `references.bib`
- `iclr2027_conference.sty`, `iclr2027_conference.bst`, `natbib.sty`, `fancyhdr.sty`
- `main.pdf.ots`, `README.md.ots` OpenTimestamps priority proofs
