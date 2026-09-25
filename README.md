# Soil Organic Carbon Mapping in Mainland Portugal

**A comparative study of Earth Observation data fusion and Google Satellite Embeddings (GSE) for 10 m SOC estimation.**

This study compares two sets of 2018 predictors: **(1)** Sentinel-1/2 imagery combined with climate and topographic variables, and **(2)** Google Satellite Embeddings. Using **428 LUCAS topsoil samples (0–20 cm)**, we evaluated Random Forest (RF), Gradient Tree Boosting (GBT), and CART. Feature selection used RFECV, with spatial cross-validation and an independent test set.

## Key results

The selected model was **RF with 33 GSE features**. Its performance was:

| Evaluation | R² | RMSE (g C kg⁻¹) | MAE (g C kg⁻¹) |
|---|---:|---:|---:|
| Spatial cross-validation | 0.34 | 19.20 | 13.20 |
| Independent validation (43 samples) | 0.44 | 19.89 | 15.50 |

GSE offered a modest improvement over conventional EO covariates. The resulting maps show broad regional SOC patterns; predictions at individual pixels should be interpreted cautiously.

## Maps

### Predicted SOC (10 m)
<img width="670" height="920" alt="image" src="https://github.com/user-attachments/assets/4cfaca82-17c5-443c-bbc5-ea011a614fe0" />



### Calibrated RF ensemble uncertainty
<img width="670" height="918" alt="image" src="https://github.com/user-attachments/assets/f6514a0e-d61c-4da0-98c6-e7043b7ccfb1" />

## Research Article
Read the full paper using below DOI


