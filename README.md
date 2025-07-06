# 🧠 Predictive Model for Pressure Injury Progression

> AI-driven healthcare project focused on predicting pressure injury outcomes using multimodal data from infrared imagery and EHR records.

---

## 📘 Project Overview

This project focuses on building a predictive model to assess and classify pressure injury progression. It integrates structured clinical data (CSV) and infrared image-based time-series data (HDF5) to predict a numeric score representing patient condition, which is then interpreted into categories: **"worst"**, **"no change"**, or **"better"**.

---

## 🔑 Key Features

- 🔗 **Data Integration**: Combines structured EHR data and time-series sensor data (infrared) for richer context.
- 🧪 **Flexible Feature Extraction**: Aggregates raw or statistical features from HDF5 files for model input.
- 🧠 **Model Training**: Trains models using algorithms like `RandomForestRegressor` and `LASSO`.
- 📈 **Condition Classification**: Maps predicted score into clinically meaningful outcomes.
- 🧩 **Modular Architecture**: Easily extendable design for new data inputs or models.

---

## 📁 Project Structure

```
project-root/
├── data/           # Input CSV and HDF5 files
├── notebooks/      # EDA and experimentation in Jupyter Notebooks
├── src/            # Source code: preprocessing, feature extraction, modeling
├── models/         # Saved models and prediction scripts
└── README.md       # Overview and documentation
```

---

## 🚀 Usage

1. **Prepare Data**: Place your `.csv` and `.h5` files in the `data/` directory.
2. **Feature Extraction**: Run scripts to extract and align HDF5 features with the CSV data.
3. **Train Model**: Use included ML scripts to train models and evaluate performance.
4. **Make Predictions**: Input a new `.h5` file to predict scores and classify the condition.

---

## 🏆 Key Achievements

- 📊 Achieved up to **90% prediction accuracy** using Random Forest and LASSO regression models.
- 🔍 Integrated multimodal data (infrared + EHR) for high-resolution predictive modeling.
- 📈 Evaluated models using AUC-ROC, confusion matrices, and classification accuracy.
- 📚 Conducted extensive literature review to guide feature engineering and temporal modeling.
- 🧠 Built an AI-powered clinical decision support prototype with real-world applicability.

---

## 🤝 Contributing

We welcome contributions! Feel free to fork the repo, open issues, or submit pull requests with improvements, ideas, or bug fixes.

---

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- Libraries: `pandas`, `h5py`, `scikit-learn`, `numpy`, `matplotlib`
- Thanks to all contributors of open-source tools used in this project.

---

## 📬 Contact

**Abdul Hannan**  
📧 [abdulhannan.shaikhh@gmail.com](mailto:abdulhannan.shaikhh@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/abdulhannan-shaikh/)  
💻 [GitHub](https://github.com/abdulhannan-99)

---

**Empowering clinical decisions through data-driven insights and AI.**
