# seattle-library-checkout-analysis
Statistical analysis of Seattle Public Library checkout patterns using Python, regression models, hypothesis testing, and ANOVA.

[![Python](https://img.shields.io/badge/Python-3.8+-blue)]()
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)]()
[![License](https://img.shields.io/badge/License-MIT-green)]()
[![Status](https://img.shields.io/badge/Status-Complete-success)]()

##  Quick Insights
- **45.7%** of checkout variance explained by material type
- **Digital checkouts** growing (slightly lower than physical)
- **Negative Binomial** distribution fits best (not Poisson)
- Top materials: **Audiobooks > Video Discs > eBooks**

##  Project Structure
The repository is organized as follows:
seattle-library-analysis/
├── DataDescription and Visualization.ipynb/ # Jupyter notebooks for data analysis
├── Distributions and regression.pdf/ # Generated visualizations (if any)
├── Hypothesis Testing # Complete project report
├── README.md
├── Summary Statistics.ipynb
└── report.pdf # This file


## 🚀 Getting Started
```bash
# Clone the repository
git clone https://github.com/yourname/seattle-library-analysis.git
cd seattle-library-analysis

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook notebooks/analysis.ipynb

Key Visualizations 
https://figures/checkouts_by_year.png
*Annual checkout trends (2005-2017)*

https://figures/material_types.png
Most popular material types in Seattle Public Library

Team
Gracious Zigara

Friday Ajinkya

Lilian Wierzbicki

Jude Reilly Polotaye

*MA 541 - Statistical Methods, Fall 2025*
Instructor: Hong Do

Full Report
Download the complete 16-page analysis: report.pdf
