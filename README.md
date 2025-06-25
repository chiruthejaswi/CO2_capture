# CO₂ Solubility Prediction in Ionic Liquids Using Machine Learning

## 🌍 Project Overview

This project focuses on predicting the **solubility of CO₂ in ionic liquids** using **molecular descriptors** derived from SMILES strings. It combines **chemistry** and **machine learning** to support carbon capture research.

We extract meaningful features from ionic compound structures and train ML models such as **Random Forest** and **Gradient Boosting** to predict CO₂ solubility under varying conditions of **temperature** and **pressure**.

---

## 🧪 Problem Statement

> **Goal:** Predict the solubility of CO₂ in ionic liquids given:
> - Molecular structure of cation and anion (SMILES)
> - Temperature and pressure conditions

Understanding and improving solubility predictions can help design better solvents for **carbon capture and storage (CCS)** technologies.

---

## 📊 Features Used

Molecular descriptors were generated using RDKit:

- `MolWt` (Molecular Weight): Heavier ions allow more CO₂ absorption.
- `NumHAcceptors` (HBA): Weakly attracts CO₂ via electrostatic forces.
- `NumHDonors` (HBD): Excess polarity repels non-polar CO₂.
- `Temperature (T)`: High temperatures decrease solubility (exothermic process).
- `Pressure (P)`: High pressure increases solubility (Henry’s Law).

---

## 🧠 ML Models

### ✅ Random Forest Regressor
- Captures non-linear patterns
- Robust to outliers
- Feature importance analysis
- `n_estimators=1000`

### 🚀 Gradient Boosting (XGBoost, LightGBM)
- Improved performance in many regression problems
- Considered for future enhancement

---

## 📁 Project Structure


