# Wildfire Damage Modeling

## Project overview

We study whether pre-fire terrain, vegetation, and fuel context can help predict where structural damage is more likely after a wildfire. We aggregate structure-level damage inspection records to **H3 hexagons**, engineer terrain and LANDFIRE-based features, build visualizations, and compare classification models for hex-level damage prediction.

Our workflow is organized into three main notebooks:

- `data_extraction_and_feature_engineering.ipynb`  
  Builds the hex-level dataset by aggregating damage inspections and attaching terrain, vegetation, and fuel features.

- `data_visualizations.ipynb`  
  Produces map-based visualizations and exported figures from the cleaned wildfire context data.

- `wildfire_damage_model_selection.ipynb`  
  Compares classification pipelines and selects a final model for wildfire damage prediction.
## Authors

Markus Hoehn and Leonard Collomb

## Poster

![Project poster](poster.jpg)
