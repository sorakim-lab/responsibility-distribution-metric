# Responsibility Distribution Metric (RCI)
A multi-layer computational index for accountability concentration 
in regulatory investigations.

## Research Question
Can responsibility concentration be measured as a unified computational 
signal across linguistic, structural, and process-level representations — 
and if so, which layer dominates in regulatory enforcement documents?

## Key Findings
→ Process-structural signal dominates RCI (w = 0.995): accountability 
  concentration in FDA enforcement documents is primarily structural, 
  not linguistic
→ WL2018-05 identified as rank 1/50 across all weight schemes — 
  extreme convergence case is weight-invariant
→ Two layers are empirically independent (VIF = 1.03): process-structural 
  and linguistic signals measure distinct dimensions of concentration
→ FDA corpus exhibits structural pre-convergence: Firm attribution 
  dominates (99%) due to enforcement document logic, not investigative 
  reasoning

## Methods
PCA (process + structural compression, PC1 = 98.6%) · RidgeCV weight learning  
Shannon entropy · Gini coefficient · Sensitivity analysis · VIF check

## Dataset
FDA Warning Letter corpus (N=50, 160 violations, 2016–2025)  
21 CFR 210/211, finished pharmaceutical manufacturing

## Related Projects
- [Premature Convergence Detection](https://github.com/sorakim-lab/premature-convergence-detection)
- [Accountability Graph Extraction](https://github.com/sorakim-lab/accountability-graph-extraction)
- [Responsibility Attribution Prediction](https://github.com/sorakim-lab/responsibility-attribution-prediction)

## Reference
Kim, S. (2026). Premature Accountability Convergence. SSRN Preprint.
