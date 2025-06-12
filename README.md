# EEG Seizure Detection with Explainable Deep Learning

This repository focuses on the detection of epileptic seizures using EEG signals through deep learning architectures, with an emphasis on interpretability using Explainable AI (XAI) techniques.

---

## 🧠 Contribution: Sijal

### 📁 File: `XAI_EEG_Sijal.ipynb`

This notebook presents a deep learning pipeline for EEG signal classification using a hybrid architecture, along with post-hoc interpretability using SHAP.

#### 🧩 Key Components:
- **Signal Preprocessing**:
  - Standardization and reshaping of EEG input signals
- **Model Architecture**:
  - **Convolutional Neural Network (CNN)**: Spatial feature extraction
  - **Bidirectional LSTM (BiLSTM)**: Temporal pattern learning
  - **Fully Connected Layers**: Final classification
- **Model Evaluation**:
  - Accuracy, loss curves, and classification performance metrics
- **Explainable AI (XAI)**:
  - Integration of **SHAP (SHapley Additive exPlanations)** to analyze feature contributions
  - Visualization of model explanation in temporal and channel-specific contexts

#### 🔧 Tools & Libraries:
- Python (Google Colab)
- TensorFlow / Keras
- SHAP
- NumPy, Pandas, Matplotlib

---

### 🎯 Objective

To develop a hybrid deep learning model for EEG-based seizure detection and apply model-agnostic interpretability techniques to enhance transparency and clinical trustworthiness of predictions.

---

### 📌 Notes
- This work is part of a broader bioinformatics project exploring AI-driven neurodiagnostic tools.
