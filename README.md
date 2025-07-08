# Predicting T Cell Expansion from Cell Spreading

Welcome to the official repository for: 📘 Predicting Mechanosensitive T Cell Expansion from Cell Spreading

Integrating morphometric feature analysis and deep learning to classify T cell types and predict their expansion potential using image-based biomarkers.

🚀 Project Summary
T cell behavior is shaped by complex biophysical cues, including surface stiffness. This project uses a combination of classical machine learning and deep learning (Swin Transformer) to analyze image-based morphometric data from CD4⁺ and CD8⁺ T cells cultured on hard vs. soft surfaces.  

We developed pipelines to: 
- 📊 Classify Healthy vs. CLL T cells
- 📈 Predict Expansion Index from T Cell Spreading Images
- 🔍 Analyze how surface rigidity affects activation and exhaustion

🧠 Key Features
- ✅ Classical ML with Decision Tree and Random Forest on morphological features
- 🧠 Deep Learning with Swin Transformer on patch-level image data
- 🔬 Morphological profiling of cell spreading on tunable surfaces
- 📁 Organized codebase for reproducibility and extension

🗂️ Repository Structure
Predicting-TCell-Expansion/ 
├── ml/                # Machine learning models on morphometric data 
├── dl/                # Deep learning notebooks (Swin Transformer, regression) 
├── notebooks/         # Original .ipynb files 
├── data/              # Placeholder for datasets 
├── figures/           # Plots and model outputs 
├── requirements.txt   # Python dependencies └── README.md          # Setup instructions and usage

🔧 Getting Started
```bash git clone https://github.com/MicroscaleBiocomplexityLaboratory/Predicting-TCell-Expansion.git cd Predicting-TCell-Expansion pip install -r requirements.txt ```
Open the notebooks in `notebooks/` or `ml/` and follow the steps for classification or regression.

📬 Contact
Developed by the Microscale Biocomplexity Laboratory Columbia University GitHub: https://github.com/MicroscaleBiocomplexityLaboratory
