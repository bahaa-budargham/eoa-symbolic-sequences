## Interactive Visualizer

An interactive analysis tool for this sequence is available:

- **Live tool:** [https://bahaa-budargham.github.io/eoa-symbolic-sequences/visualizer/](https://bahaa-budargham.github.io/eoa-symbolic-sequences/visualizer/)
- **Frozen report:** [`reports/eoa_sequence_visualizer_letter_a_LCR_3.14.html`](report/eoa_sequence_visualizer_letter_a_LCR_3.14.html)

Paste the released word (or any symbolic sequence) into the tool to generate
twelve analytical panels in real time:

| # | Panel | What it measures |
|---|-------|------------------|
| 1 | Symbolic Turtle Rendering | Geometric embedding of the sequence under a deterministic symbol→angle map |
| 2 | Chaos Game Representation | Density of symbol transitions; forbidden pairs appear as empty regions |
| 3 | Recurrence Plot | Repeated subword structure at all length scales |
| 4 | Rewrite Engine | Optional user-supplied morphism σ; renders the resulting word class |
| 5 | Empirical Eigenvector Projection | Prefix Parikh walk projected onto the empirical contracting plane |
| 6 | Subword Transition Graph | Order-n factor graph; node degree and spectral radius |
| 7 | Desubstitution Test | Whether the word parses uniquely under a candidate σ |
| 8 | Factor Complexity p(k) | Distinct length-k subwords, log-log with Sturmian and linear baselines |
| 9 | Abelian Complexity a(k) | Distinct Parikh vectors of length-k factors |
| 10 | Finite-Sample Block-Growth Ladder | Sofic bounds log ρ(G_k) vs the empirical growth rate (1/n)·log p(n) |
| 11 | Prefix-Frequency Discrepancy | Max deviation of prefix symbol counts from the asymptotic frequency vector |
| 12 | Surrogate Controls | Original vs frequency-shuffle, Markov order-1, and periodic controls |

Every panel carries a caption stating what is **observed**, what is **estimated
from a chosen model**, and what remains an **open hypothesis**. No claim about the
infinite-limit behaviour of the sequence is made by the tool.

**Export.** The tool produces a self-contained HTML report embedding all twelve
panels as PNGs, the SHA-256 of the input word, and a three-tier metrics table
(Observed / Estimated / Hypothesis). The report is the frozen artifact; the tool
is the re-runnable process.
