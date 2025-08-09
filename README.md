
# Breast Cancer Diagnosis Prediction

This project applies machine learning classification techniques to predict whether a breast tumor is Malignant or Benign, based on diagnostic features. It also forecasts recurrence or non-recurrence of malignant cases after a specific period. The aim is to assist in early detection, enabling timely treatment and improving patient outcomes.

Projektbeschreibung (Deutsch):

Dieses Projekt nutzt maschinelles Lernen, um Brustkrebsfälle als gutartig oder bösartig zu klassifizieren und mögliche Rückfälle vorherzusagen. Die Daten wurden vorverarbeitet und mit verschiedenen Klassifikationsalgorithmen analysiert. Ziel ist es, medizinische Diagnosen zu unterstützen und eine präzisere Risikobewertung zu ermöglichen.

## Author

Nafeesath Parappurath Puthiyapurayil
MSc. Data Science

📍 Berlin, Germany

📧 nafizaumar@gmail.com

💼 https://www.linkedin.com/in/nafeesath/



## Acknowledgements

Special thanks to:

- UCI Machine Learning Repository for the dataset.

- Open-source Python libraries used in this project.

- Mentor, Prof. Dr. Iftikhar Ahmed (University of Europe for Applied Sciences, Potsdam, Germany) and peers for guidance during project development.


## Objectives
- Classify breast cancer cases into Malignant or Benign.

- Predict recurrence risk for malignant cases.

- Compare performance of multiple ML classification algorithms.

## Technologies Used

- Programming Language: Python 3.x

- Libraries:

1. Pandas, NumPy (Data Processing)

2. Matplotlib, Seaborn (Visualization)

3. Scikit-learn (ML Models & Evaluation)

- Tools: Jupyter Notebook

## Dataset
- Source: UCI Machine Learning Repository – Breast Cancer Dataset
(https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

- Type: Tabular medical dataset

- Features: Tumor size, cell shape, texture, smoothness, etc.

- Labels: Benign (B) or Malignant (M)

## Methodology
- Data Loading & Preprocessing – Handle missing values, encode categorical features.

- Exploratory Data Analysis (EDA) – Visualize distributions & correlations.

- Feature Selection – Identify most important predictors.

- Model Training – Logistic Regression, Decision Tree, Random Forest, SVM.

- Evaluation – Accuracy, Precision, Recall, F1-score, Confusion Matrix.

- Prediction – Classify new data points.

## Results

- Best Model: Random Forest Classifier
- Accuracy: 96%
- Precision: 95% (Malignant), 97% (Benign)
- Recall: 94% (Malignant), 98% (Benign)



## Lessons Learned

1. Early detection through ML models can improve diagnosis speed and accuracy.

2. Random Forest gave the best performance for this dataset.

3. The approach can be adapted for other medical classification problems.



## Future Scope

- Implement deep learning models (e.g., CNNs) for higher accuracy.

- Deploy as an interactive web app for real-time cancer prediction.

- Integrate with medical imaging (e.g., mammograms) for enhanced diagnosis.

- Expand dataset for better generalization to diverse patient profiles.

## License

This project is licensed under the MIT License – free to use for educational purposes.