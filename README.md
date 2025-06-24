# cancer-metastasis-prediction
Machine learning on gene expression to predict cancer metastasis
# 🧬 Breast Cancer Metastasis Prediction (GSE40206)

This project uses machine learning to predict breast cancer metastasis based on gene expression profiles from the GEO dataset **GSE40206**. It integrates data preprocessing, model training, performance evaluation, and feature importance analysis.

---

## 📌 Overview

- 🔍 **Objective**: Predict metastatic vs. non-metastatic samples
- 🧪 **Data Source**: [GEO - GSE40206](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE40206)
- 🛠️ **Tech Stack**: Python, GEOparse, scikit-learn, matplotlib, seaborn
- 📁 **Platform**: Illumina HumanHT-12 V4.0 expression beadchip

---
## 🚀 Workflow

1. **Data Extraction**: Load raw expression data from `.soft` file using GEOparse
2. **Annotation**: Map probe IDs to gene symbols
3. **Preprocessing**: Clean missing values, scale data, add binary labels
4. **Model Training**: Random Forest classifier
5. **Evaluation**: Accuracy, confusion matrix, ROC-AUC
6. **Feature Analysis**: Identify top genes contributing to classification

---

## 📊 Results

### 🔬 Top 20 Important Genes
> Barplot showing genes with highest feature importance  
📁 [`results/top_20_genes.png`](./results/top_20_genes.png)

### 🧪 ROC Curve
> Visualizes model’s ability to distinguish between classes  
📁 [`results/roc_curve.png`](./results/roc_curve.png)


## 📦 Requirements

Install dependencies using pip:

```bash
pip install -r requirements.txt
```


## ⚠️ Disclaimer

This project is for research and academic purposes only. It is **not** intended for clinical diagnosis or patient decision-making.

---

## 👩‍💻 Author

**Arushi Gupta**  
M.Sc. Bioinformatics   
Institution: Amity University, Noida
