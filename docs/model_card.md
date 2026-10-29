# Model card — Computer Vision Quality Inspection System

Task: vision; source: Synthetic patterned images of simulated defects.

## Evaluation
- Logistic Regression: PR-AUC = 1.0000
- Random Forest: PR-AUC = 1.0000

Split: group by simulated source. The supplied results are deterministic educational demonstrations, not real-world benchmarks or deployment approvals.

## Risks
Training data is synthetic. Statistical estimates may not transfer to real events. Audit fairness, calibration, input distributions, access controls and domain-specific safety before external use.
