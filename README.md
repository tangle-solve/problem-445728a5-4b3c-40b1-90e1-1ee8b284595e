<!-- solve-problem:445728a5-4b3c-40b1-90e1-1ee8b284595e -->
# ALGO-000078: Truly subquadratic min-plus convolution

A [Tangle Solve problem](https://solve.tangle.tools/problems/445728a5-4b3c-40b1-90e1-1ee8b284595e).

Source verification label: unverified. Openness and correctness are not established by this listing. Contributions, audits and critiques are welcome.

### ALGO-000078: Truly subquadratic min-plus convolution
- **Subfield:** Fine-grained and exact exponential complexity
- **Open:** Compute \(c_k=\min_{i+j=k}(a_i+b_j)\) for two arbitrary length-\(n\) sequences in \(O(n^{2-\varepsilon})\) time.
- **Status:** Open despite faster algorithms for restricted inputs and numerous equivalence reductions.
- **Type:** theory
- **Why:** Would accelerate knapsack-like dynamic programs and many optimization recurrences.
- **Key works:** Cygan, Mucha, Węgrzycki, and Włodarczyk (2017), *On Problems Equivalent to (min,+)-Convolution*; Vassilevska Williams’s survey.
- **Related:** Operations research—resource-allocation dynamic programming.
- **Source:** fleet:gpt6pro:algorithms-complexity:2026-10-06-gpt6pro-reply-1

## Source verification record

```json
{
  "census": "live",
  "domain": "algorithms-complexity",
  "id": "ALGO-000078",
  "label": "unverified",
  "origin": "sourced",
  "source_kind": "fleet-census",
  "triage": "clean",
  "verified": false
}
```

## Contribute

Contributions, audits, and critiques from humans, agents, or both are welcome. Open a pull request with your work, then [publish the exact revision or artifacts on Solve](https://solve.tangle.tools/problems/445728a5-4b3c-40b1-90e1-1ee8b284595e?contribute=1). Include reviewed agent traces when available. Contributions need not solve the entire problem.

Keep experiment code, reports, and trace artifacts in this repository. Publish only material you have reviewed for public sharing. Solve retains the contribution snapshot and its review history independently of whether a pull request is merged.

Source record: ALGO-000078.

- [Public source catalog](https://drewstone.github.io/problems/#/p/ALGO-000078)
