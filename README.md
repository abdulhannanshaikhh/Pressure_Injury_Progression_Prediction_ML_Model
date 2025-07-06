# Predictive Model for Pressure Injury Progression

![Built With](https://img.shields.io/badge/Built%20With-Python%20%7C%20Scikit--learn%20%7C%20pandas%20%7C%20numpy%20%7C%20h5py-blueviolet)

> An AI-driven healthcare project that predicts the progression of pressure injuries using multimodal clinical and sensor data.

---

## 📘 About the Project

This project focuses on developing a machine learning model to **predict the progression of pressure injuries** in patients by analyzing data from both electronic health records (CSV) and infrared sensor files (HDF5). The output score is used to classify a patient’s condition as **“worst,” “no change,” or “better.”**

The project is built with a modular architecture for easy adaptation and extensibility, and it is designed to support **real-world clinical decision-making** through AI-driven insights.

---

## 🧠 Key Features

- 🔗 **Multimodal Data Integration**: Combines structured EHR data and time-series IR data (from HDF5).
- 🧪 **Feature Engineering**: Extracts and aggregates meaningful features for modeling.
- 🤖 **ML Model Training**: Supports Random Forest and LASSO Regression models.
- 📊 **Outcome Classification**: Translates regression scores into clinically interpretable categories.
- 🧩 **Modular & Extendable**: Flexible codebase for adapting to new data and models.

---

## ⚙️ Tech Stack

| Category            | Tools Used                                     |
|---------------------|------------------------------------------------|
| **Programming**     | Python                                         |
| **ML Libraries**    | scikit-learn, pandas, numpy                    |
| **Data Formats**    | CSV (EHR), HDF5 (sensor data)                  |
| **Visualization**   | matplotlib, seaborn                            |
| **Model Types**     | Random Forest Regressor, LASSO Regression      |
| **Version Control** | Git, GitHub                                    |

---

## 🏆 Project Highlights

- 📊 Achieved **90%+ accuracy** using Random Forest and LASSO models.
- 🧠 Integrated multimodal sensor + clinical data for high-fidelity predictions.
- 🧪 Evaluated using AUC, ROC, confusion matrices, and classification accuracy.
- 📚 Literature review-informed feature engineering & data preprocessing.
- 🏥 Developed with a focus on clinical relevance and reproducibility.

---

## 🤝 Contributions

We welcome contributions from the GitHub community!

- Fork the repository
- Create your feature branch: `git checkout -b feature/feature-name`
- Commit your changes: `git commit -m "Add new feature"`
- Push to the branch: `git push origin feature/feature-name`
- Open a pull request

---

## 🙏 Acknowledgements

- Tools & Libraries: `pandas`, `h5py`, `scikit-learn`, `numpy`, `matplotlib`
- Mentorship & Research Support from Taipei Medical University

---
