# Stochastic Interest Rate Modelling and Prediction

**Finance Club, IIT Roorkee — Open Projects 2026**

Implementation, calibration, and extension of the Cox-Ingersoll-Ross (CIR) 
model on real historical yield curve data.

## Results
- Out-of-sample R² = **0.9211** (target > 0.85 ✓)
- Evaluated on 495 test days (Apr 2024 – Apr 2026)
- Yield curve reconstructed from **3M rate only**

## Project Structure

* `data/` — raw CSV files (train, test, test_3M)
* `notebooks/` — cir_model.ipynb (single deliverable notebook)

## Google Colab

[Open notebook in Colab](https://colab.research.google.com/drive/1oN4xYBuIeimUcDEqPl7ivRf0w36zvD_I?usp=sharing) 

## Requirements

To run this locally, install the dependencies:

```bash
pip install -r requirements.txt