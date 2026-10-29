
# 🧪 Superconductor Critical Temperature Prediction (Deep Learning)

An end-to-end Deep Learning regression project built with **PyTorch** to predict the critical temperature (\(T_c\)) of superconducting materials based on their physical and chemical properties.

📌 Project Overview
Discovering new superconductor materials and predicting their critical temperatures is a major challenge in material science. This project utilizes a Multi-Layer Perceptron (MLP) built with PyTorch, trained on the Kaggle Superconductivty dataset, to model the complex, non-linear relationships between 81 material features and their critical temperatures.

📊 Dataset Information
Source: Kaggle Superconductivty Data Set

Size: 21,263 entries

Features: 81 physical/chemical features (e.g., atomic mass, valence, thermal conductivity, entropy).

Target Variable: critical_temp (Continuous value in Kelvin).

🏗️ Tech Stack
Language: Python 3.x

Deep Learning Framework: PyTorch

Data Processing & EDA: Pandas, NumPy, Scikit-Learn

Visualization: Seaborn, Matplotlib

Deployment: Streamlit