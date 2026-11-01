# Machine learning prediction of CO2 uptake in MOFs at post-combustion conditions

Random forest model predicting CO2 uptake (mmol/g) at 0.15 bar and 298 K, the adsorption
step of a post-combustion vacuum swing adsorption cycle, from eight Zeo++ geometric
descriptors for 20,000 MOFs sampled from the ARC-MOF database.

**Key results**
- 5-fold cross-validation: R² = 0.59, MAE = 0.38 mmol/g
- Accessible void fraction is the dominant descriptor: compact frameworks with low void
  fraction and small cavities, but accessible pore openings, favour low-pressure uptake
- The model systematically underpredicts the highest-uptake MOFs, consistent with
  low-pressure CO2 adsorption being governed by binding chemistry that geometric
  descriptors cannot capture

**Data:** ARC-MOF database (Burner et al., University of Ottawa), Zenodo:
https://zenodo.org/records/16802743
