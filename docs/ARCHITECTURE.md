# Real Estate Housing Market Analytics & Price Prediction - Architecture & Pipeline Design

```mermaid
graph TD
    DataInput[Raw CSV Dataset: Housing.csv] --> Preproc[Data Cleaning & Column Transformer]
    Preproc -->|Numeric| Scaler[StandardScaler Normalization]
    Preproc -->|Categorical| Encoder[One-Hot Categorical Encoding]
    Scaler --> Split[Train/Test Stratified Split 80/20]
    Encoder --> Split
    Split --> Train[Model Training: Random Forest Regressor]
    Train --> Eval[Evaluation & Benchmarks]
    Eval --> Inference[Production Inference & CLI]
```

## Comparative Models Evaluated
- **Random Forest Regressor**
- **XGBoost Regressor**
- **Ridge Regression**
- **ElasticNet**
