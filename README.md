# Dacon_Pharmaceuticals

Development of a Prediction Model for CYP3A4 Enzyme Inhibition in Human Drug Metabolism

- A prediction model was developed using a training dataset of 1,681 compounds, which includes their chemical structures and CYP3A4 enzyme inhibition rates (% inhibition). The model will be used to predict inhibition rates for a competition's evaluation dataset.

- train data: 1,681 compounds related to CYP3A4 enzyme inhibition.
    - ID: Unique identifier
    - Canonical_Smiles: Molecular structure data
    - Inhibition: Inhibition rate (unit: %)

- Results
  - Score: 0.64672
  - Rank: 224th out of 763 teams
  - Performance was evaluated based on the following formula

    A = Normalized RMSE for Inhibition(%)
    
    B = Pearson Correlation Coefficient between predicted and actual values

    Score=0.5×(1−min(A,1))+0.5×B
