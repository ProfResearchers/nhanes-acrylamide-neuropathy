# Hemoglobin Adducts of Acrylamide and Glycidamide and Peripheral Neuropathy in U.S. Adults: NHANES 2003–2004

[![DOI](https://zenodo.org/badge/DOI/10.17605/OSF.IO/YOUR_DOI_HERE.svg)](https://doi.org/10.17605/OSF.IO/YOUR_DOI_HERE)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/nhanes-acrylamide-neuropathy/blob/main/NHANES_Acrylamide_Neuropathy_Supplementary_Analysis.ipynb)

This repository contains the complete, fully reproducible computational pipeline and merged dataset accompanying the manuscript: **"Hemoglobin Adducts of Acrylamide and Glycidamide and Peripheral Neuropathy in U.S. Adults: A Cross-Sectional Analysis of NHANES 2003–2004"**.

## Abstract
Acrylamide, a probable human carcinogen and established neurotoxicant found in heated foods and tobacco smoke, has been linked to peripheral neuropathy... [Add a brief abstract here].

---

## Repository Contents

* `NHANES_Acrylamide_Neuropathy_Supplementary_Analysis.ipynb`: The complete Python/R dual-pipeline. It programmatically downloads public-use CDC raw files, merges them, fits all models, and generates final publication-quality figures.
* `analytic_full.csv`: The compiled analytic dataset containing the 2,266 participants aged ≥40 years used in this study.
* `figures/`: High-resolution PDFs and vector graphics generated directly by the notebook models.

---

## How to Reproduce this Study

### Option 1: Run in Google Colab (One-Click)
Click the **"Open in Colab"** badge at the top of this page. This runs the notebook entirely in the cloud. It will download the CDC datasets programmatically, so you do not need to download anything locally.

### Option 2: Run Locally
1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_GITHUB_USERNAME/nhanes-acrylamide-neuropathy.git
   cd nhanes-acrylamide-neuropathy
