# OpenADMET-ExpansionRx-Blind-Challenge
This repository describes my submission to the OpenADMET-ExpansionRx Blind Challenge
- **Author**: Ruel Cedeno, PhD
- **Date**: December 2025

## Methodology Report
**Algorithms**: weighted average ensemble of multiple models 
- Message passing neural network (MPNN) as implemented in ChemProp 2.2
- Transformer pretrained on tabular data as implemented in TabPFN v2
- Classical tree based models: Random Forest, LightGBM, XGBoost 
  
**Additional features**  
We explored various molecular representations including:
- ECFP4
- Avalon
- RDKit-2d
- Mordred
- ADMET-AI predictions
- Learned embeddings: CheMeleon, MiniMol, CLAMP

**Additional Data**
- Only publicly available data were leveraged
- These data were used for feature augmentation (not directly concatenated with the provided ExpansionRx training set). 

**Performance comments**  
- Our internal cross-validation metrics are comparable to the live leaderboard scores.
- The endpoints MPPB, MBPB, and MGMB have more variability. 

**Reference**  
Our approach is similar to my submission to the *ASAP-Polaris-OpenADMET Challenge* described in our recent publication

Deep Learning vs Classical Methods in Potency and ADME Prediction: Insights from a Computational Blind Challenge.  
*J. Chem. Inf. Model. 2025, 65 (24), 13115–13131.*

- [JCIM Article](https://doi.org/10.1021/acs.jcim.5c01982) 
- [ChemRxiv Preprint](https://doi.org/10.26434/chemrxiv-2025-64fcb-v3) 




