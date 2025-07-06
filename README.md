# 🧠 Predictive Model for Pressure Injury Progression

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Built With](https://img.shields.io/badge/Built%20With-Python%20%7C%20Scikit--learn%20%7C%20pandas%20%7C%20h5py-blueviolet)

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

## 📁 Project Structure

```
project-root/
├── data/           # Input CSV and HDF5 files
├── notebooks/      # EDA and model experiments in Jupyter
├── src/            # Source code for preprocessing and modeling
├── models/         # Trained models and prediction scripts
└── README.md       # Project overview and documentation
```

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- pip / virtualenv

### Installation

1. Clone the repository  
```bash
git clone https://github.com/your-username/pressure-injury-prediction.git
cd pressure-injury-prediction
```

2. Create virtual environment and install dependencies  
```bash
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
pip install -r requirements.txt
```

3. Prepare your data  
- Place your `.csv` and `.h5` files in the `data/` directory.

4. Run feature extraction & model training scripts  
```bash
python src/train_model.py
```

5. Make predictions  
```bash
python src/predict_condition.py --input data/sample_new.h5
```

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

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙏 Acknowledgements

- Tools & Libraries: `pandas`, `h5py`, `scikit-learn`, `numpy`, `matplotlib`
- Mentorship & Research Support from Taipei Medical University

---

## 📬 Contact

**Abdul Hannan**  
📧 [abdulhannan.shaikhh@gmail.com](mailto:abdulhannan.shaikhh@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/abdulhannan-shaikh/)  
💻 [GitHub](https://github.com/abdulhannan-99)

---

**Bringing AI into healthcare to empower early intervention and save lives.**
