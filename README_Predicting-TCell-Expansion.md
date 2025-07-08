# Predicting T Cell Expansion from Cell Spreading

This repository contains code and data for the study: predicting mechanosensitive T cell expansion potential based on cell spreading morphology. Both deep learning and machine learning approaches are included.

## Structure
- `ml/`: Classical ML using morphological features
- `dl/`: Deep learning models (Swin Transformer, Regression)
- `data/`: Input data (not included)
- `notebooks/`: Original Jupyter notebooks
- `figures/`: Visualizations and plots


## Setup Instructions
To install the required dependencies, run:

```bash
pip install -r requirements.txt
```

Make sure you have Python 3.10 installed. You can then open the Jupyter notebooks inside the `notebooks/` folder or run scripts directly.

For deep learning models:
- Run the patch generator: `Sample code_GenerateSlidingPatches_no overlap_only Hard_for HvsCLL.ipynb`
- Then run: `Sample code_HvsCLL_Hard surface_SWIN.ipynb` for classification, or `Sample code_Regression.ipynb` for regression.

For classical machine learning:
- Open and run: `Sample Code_Hard only_HvsCLL classification_3H7CLL_Image level.ipynb` inside the `ml/` folder.
