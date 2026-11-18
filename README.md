# Detector Benchmark — PRBS Scorecard

**Particle Reconstruction Benchmark Score (PRBS)**, draft v0.3: a single 0–100 score for grading
calorimeter reconstruction models on four equally weighted benchmarks:

1. Clustering
2. Energy reconstruction
3. Position reconstruction
4. Particle classification

- Web page: https://zhiwanxu.github.io/detector-benchmark/
- PDF: [`prbs_scorecard_v0.3.pdf`](prbs_scorecard_v0.3.pdf)

All results use one standard binning (10 energy bins, 10 η bins over −1.5 < η < 1.5) so results from
different groups can be compared directly. The only fit is the energy resolution
σ_E/E = A + B/√E + C/E. Every other quantity is scored bin by bin.

Status: draft. Several targets are still to be frozen (marked TBD on the page).
