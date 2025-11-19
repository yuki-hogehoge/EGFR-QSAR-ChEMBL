# EGFR QSAR Model

## Overview
Built QSAR model for EGFR inhibitors using ChEMBL IC50 data.
- Data: 3,528 compounds
- Features: Morgan FP (radius=3, 2048 bits)
- Model: XGBoost
- Final R²: 0.637

## Usage
Run `EGFR_QSAR_Project.ipynb` in Colab.

## Results
- Scaffold analysis: Quinazoline dominant in high-activity.
- Error patterns: Over-prediction in polar scaffolds.
