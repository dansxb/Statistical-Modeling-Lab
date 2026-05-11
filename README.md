# Statistical Modeling Lab

A collection of datasets and analyses exploring statistical relationships in agricultural data.

## Contents

| File | Description |
|---|---|
| `farm-yield-analysis-prediction-with-ml-models.ipynb` | EDA and ML models (Linear Regression, Random Forest, XGBoost, LightGBM, CatBoost) for crop yield prediction |
| `agriculture_dataset.csv` | Full dataset — 50 farm records, 10 variables |
| `clean_pesticide_yield.csv` | Cleaned subset — crop type, pesticide usage, and yield only |
| `requirements.txt` | Python dependencies |

## Setup

```bash
pip install -r requirements.txt
jupyter lab
```

## Datasets

### `agriculture_dataset.csv` — Full Dataset
50 farm records with a broad set of agronomic variables.

| Column | Description |
|---|---|
| `Farm_ID` | Unique farm identifier |
| `Crop_Type` | Type of crop grown |
| `Farm_Area(acres)` | Total farm area in acres |
| `Irrigation_Type` | Irrigation method (Drip, Flood, Sprinkler, Rain-fed, Manual) |
| `Fertilizer_Used(tons)` | Fertilizer applied in tons |
| `Pesticide_Used(kg)` | Pesticide applied in kilograms |
| `Yield(tons)` | Crop yield in tons |
| `Soil_Type` | Soil classification (Loamy, Clay, Sandy, Silty, Peaty) |
| `Season` | Growing season (Kharif, Rabi, Zaid) |
| `Water_Usage(cubic meters)` | Total water consumed in cubic meters |

### `clean_pesticide_yield.csv` — Cleaned Subset
Focused on the relationship between pesticide usage and crop yield.

| Column | Description |
|---|---|
| `Crop_Type` | Type of crop grown |
| `Pesticide_Used(kg)` | Pesticide applied in kilograms |
| `Yield(tons)` | Crop yield in tons |

## Source

Dataset sourced from [Kaggle — Farm Yield Analysis](https://www.kaggle.com/datasets/5913416).
