# OpenADMET-ExpansionRx-Blind-Challenge
This repository describes our submission to the OpenADMET-ExpansionRx Blind Challenge


## Methodology Report
**Algorithms**: Ensemble average of multiple models 
- Message passing neural network (MPNN) as implemented in ChemProp 2.2
- TabPFN v2
- Tree based models: Random Forest, LightGBM, XGBoost 
  
**Additional features**: We explored various molecular representations including:
- ECFP4
- Avalon
- RDKit-2d
- Mordred
- ADMET-AI predictions

### Performance comments
Our internal cross-validation metrics are comparable (within ± 10%)  to the live leaderboard scores.

