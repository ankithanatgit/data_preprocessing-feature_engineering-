# Data Preprocessing Report – Churn Prediction

## Dataset Overview
The dataset contains customer demographic, service usage, and billing information.

## Missing Values
No missing values were observed.

## Encoding Techniques
- Label Encoding: Binary categorical features
- One-Hot Encoding: Nominal variables
- Ordinal Encoding: Contract duration

## Scaling
- StandardScaler: Continuous numeric variables
- MinMaxScaler: Financial ratio-based features

## Pipeline
A complete sklearn ColumnTransformer pipeline ensures consistent preprocessing.

## Final Output

After applying feature engineering, encoding, and scaling,
the preprocessing pipeline produced a final feature matrix
of shape (200, 22), where:

- 200 represents the number of customer records
- 22 represents the transformed and engineered features

