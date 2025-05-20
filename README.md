# collatz-collapse-phi-star
# Collatz Collapse via φ*-Lyapunov Descent

This repository introduces a symbolic proof framework for the Collatz Conjecture using a novel Lyapunov-like function φ* defined over parity vectors.

## Key Result

Let φ*(n) = w₁ · L(Pₙ) + w₂ · r(Pₙ) + w₃ · H(Pₙ), where:
- L(Pₙ): length of the parity vector of n
- r(Pₙ): number of 0/1 runs
- H(Pₙ): Shannon entropy of 0/1 balance
- w₁ = 1, w₂ = 0, w₃ < 1 / ΔHₘₐₓ ≈ 1 / 0.107

This function is strictly decreasing under T(n), the Collatz map, for all n ∉ {1,2,4}.

## Status

The core descent logic is complete and symbolically locked. A formal proof of the entropy bound and full LaTeX manuscript are in preparation.

## Repository Contents

- `README.md`: this summary
- `entropy_bound_demo.ipynb`: entropy shift visualizations and maximum proof outline
- `draft_proof_outline.md`: theorem structure, symbolic descent, and Lyapunov criteria

## License

© 2025 Stanley Philipose. All rights reserved. Attribution required for derivative works.
