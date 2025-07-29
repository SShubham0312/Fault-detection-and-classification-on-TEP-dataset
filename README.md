# Fault Detection and Classification in the Tennessee Eastman Process (TEP)

This repository contains the work done as part of my internship at Engineers India Limited (EIL), focused on fault detection and classification using the **Tennessee Eastman Process (TEP)** dataset — a well-known benchmark in process monitoring and fault diagnosis research.

## 📌 Objective

The primary goal of the internship was to explore and compare various data-driven techniques for detecting and classifying faults in a complex chemical process, simulating real-world fault detection in industrial systems.

---

## 📊 Dataset

- **Source**: Tennessee Eastman Process Simulation Dataset
- **Details**:
  - Multivariate time-series process data
  - 52 variables: 41 measured variables (XMEAS), 11 manipulated variables (XMV)
  - 21 fault types (including normal operation)

---

## 🔍 Tasks & Methods

### 🧪 Fault Detection

**Goal**: Identify whether a fault has occurred.

**Methods Used**:
- **Statistical Approaches**:
  - T² Statistic (Hotelling’s T-squared)
  - Q Statistic (Squared Prediction Error)

- **Dimensionality Reduction Techniques**:
  - PCA (Principal Component Analysis)
  - DPCA (Dynamic PCA)
  - ICA (Independent Component Analysis)
  - kPCA (Kernel PCA)

- **Neural Approaches**:
  - Autoencoders

### 🔬 Fault Classification

**Goal**: Predict the type of fault that has occurred.

**Methods Used**:
- Random Forest (RF)
- XGBoost

**Metrics Evaluated**:
- Accuracy
- F1-Score
- Precision
- Recall

---

## 🧰 Tools & Technologies

- Python
- NumPy, pandas, scikit-learn
- matplotlib, seaborn
- XGBoost
- TensorFlow / PyTorch (for Autoencoders)

---

## 📈 Results

- **Detection**: PCA and Autoencoder-based approaches yielded the highest fault detection rates.
- **Classification**: XGBoost outperformed Random Forest for most fault types, particularly on imbalanced data.

---

