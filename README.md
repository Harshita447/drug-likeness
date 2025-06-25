# 🧪 Drug-Likeness Prediction from SMILES using RDKit & Machine Learning

This is a bioinformatics project built using *Python, **RDKit, and **scikit-learn* in *Google Colab*. It allows users to upload a CSV file containing SMILES strings (chemical structures), extract important molecular features, and predict whether a compound may be drug-like or not.

---

## 🚀 Features

- ✅ Upload your own CSV file with SMILES
- 🔬 Automatically extract features:
  - Molecular Weight (MolWt)
  - LogP (hydrophobicity)
  - Number of Hydrogen Bond Donors (HDonors)
- 🤖 Train a Random Forest model (for demonstration)
- 📊 View predictions and download results
- 🎨 Visualize molecules using RDKit

---

## 🧰 Tech Stack

- Python 3.x
- Google Colab
- RDKit
- pandas
- scikit-learn
- matplotlib

---

## 📂 Sample Input Format (CSV)

```csv
DrugName,SMILES
Aspirin,CC(=O)OC1=CC=CC=C1C(=O)O
Caffeine,CN1C=NC2=C1C(=O)N(C(=O)N2C)C
