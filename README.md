# Waste Classification (RealWaste)

Short overview and quick run steps for EN3150 – Learning from Data.

## What’s inside

- `CNN_comparison.ipynb`: Transfer‑learning baselines (compare pre‑trained CNNs).
- `Custom_CNN_Classifier.ipynb`: CNN trained from scratch for the 9 RealWaste classes.

## Requirements

- Python 3.8+ and Jupyter.
- Common libs: numpy, pandas, matplotlib, scikit‑learn, torch/torchvision.

## How to run (Windows PowerShell)

1. Start Jupyter: `jupyter notebook`.
2. Open a notebook and run all cells.
   - Use `CNN_comparison.ipynb` to evaluate transfer learning.
   - Use `Custom_CNN_Classifier.ipynb` to train the custom CNN.

## Notes

- Dataset: RealWaste (9 classes). Expect class imbalance; augmentation and early stopping help.
- Results: compare accuracy/F1 across custom vs transfer‑learning models.
