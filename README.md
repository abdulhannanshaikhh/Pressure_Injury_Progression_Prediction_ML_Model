# Predictive Model for Pressure Injury Progression

Project Overview
This project involves the development of a predictive model that integrates data from pressure injury patient's condition CSV and HDF5 data files. The primary goal is to predict a specific score based on features extracted from both types of files. The predicted score is then interpreted to classify conditions as "worst," "no change," or "better."

Key Features:-
- Data Integration: Combines structured data from CSV files with time-series or sensor data stored in HDF5 files.
- Flexible Feature Extraction: Allows for the extraction of raw or aggregated features from HDF5 files to be used in modeling.
- Model Training: Uses machine learning algorithms, specifically RandomForestRegressor, to predict the target score.
- Condition Classification: Interprets the predicted score into meaningful categories ("worst," "no change," "better") for easier decision-making.
- Modular Code: Functions are designed to be modular, making it easy to adapt and extend the project to new data sources or models.

Project Structure:-
- data/: Contains the input CSV and HDF5 files used for training and prediction.
- notebooks/: Jupyter notebooks for exploratory data analysis (EDA) and experimentation.
- src/: Source code for data loading, preprocessing, feature extraction, and model training.
- models/: Trained models and scripts for making predictions.
- README.md: Project overview, installation instructions, and usage guidelines.

Usage:-
- Data Preparation: Place your CSV and HDF5 files in the data/ directory.
- Feature Extraction: The script will automatically extract features from the HDF5 files and align them with the CSV data based on dates.
- Model Training: The RandomForestRegressor model is trained using the combined data, and the model's performance is evaluated.
- Prediction: Provide a new HDF5 file to predict the score and classify the condition.

Contributing:-
- Contributions are welcome! Please feel free to submit a pull request or open an issue if you find a bug or have suggestions for improvements.

License:-
- This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments:-
- This project was developed using pandas, h5py, scikit-learn, and other open-source libraries.
- Special thanks to the contributors of these libraries for providing tools that make data science accessible.
