
# Breast Cancer Detection using Machine Learning

## Project Overview

This project focuses on the detection of breast cancer using Machine Learning techniques. The goal of the project is to classify whether a tumor is **malignant (cancerous)** or **benign (non-cancerous)** based on various features extracted from breast cancer diagnostic data.

Machine Learning models can help in early detection of breast cancer, which can assist doctors in diagnosis and decision making.

---

## Problem Statement

Breast cancer is one of the most common cancers among women worldwide. Early detection plays a very important role in improving survival rates. However, manually analyzing medical data can be difficult and time-consuming.

This project uses Machine Learning to build a classification model that predicts whether a tumor is malignant or benign based on input features.

---

## Dataset

The dataset used in this project is the **Breast Cancer Wisconsin (Diagnostic) Dataset**.

This dataset is available from the Scikit-Learn library:

```python
from sklearn.datasets import load_breast_cancer
```

The dataset contains several features computed from digitized images of breast mass, such as:

* Radius
* Texture
* Perimeter
* Area
* Smoothness
* Compactness
* Concavity
* Symmetry
* Fractal dimension

These features are used to train the machine learning model.

---

## Project Workflow

The project follows the complete Machine Learning pipeline:

1. Import required libraries
2. Load dataset
3. Data exploration and visualization
4. Data preprocessing and normalization
5. Split dataset into training and testing sets
6. Train machine learning model
7. Predict test results
8. Evaluate model performance
9. Display confusion matrix and accuracy

Workflow diagram:

```
Dataset → Data Analysis → Preprocessing → Train Model → Test Model → Accuracy
```

---

## Exploratory Data Analysis (EDA)

In this step:

* Dataset structure is analyzed
* Feature relationships are visualized
* Correlation heatmap is plotted
* Scatter plots are created
* Data distribution is analyzed

EDA helps in understanding which features are important for prediction.

---

## Machine Learning Algorithm Used

The main algorithm used in this project is:

### Support Vector Machine (SVM)

Support Vector Machine is a supervised machine learning algorithm used for classification problems.
It works by finding an optimal hyperplane that separates data points into different classes.

SVM performs well for high-dimensional datasets and classification problems, which makes it suitable for this breast cancer detection problem.

---

## Model Training

Steps involved in model training:

1. Data normalization
2. Splitting data into training and testing sets
3. Training the SVM model
4. Predicting test data
5. Evaluating model performance

---

## Model Evaluation

The model is evaluated using:

* Confusion Matrix
* Classification Report
* Accuracy Score

The confusion matrix shows:

* True Positives
* True Negatives
* False Positives
* False Negatives

---

## Results

The model achieved an accuracy of approximately:

```
96% – 97%
```

Accuracy improved after:

* Data normalization
* Parameter optimization (C and Gamma in SVM)

This shows that the SVM model performs very well for breast cancer classification.

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook
* Machine Learning (SVM)

---

## How to Run the Project

1. Clone the repository
2. Install required libraries
3. Open Jupyter Notebook
4. Run all cells

Commands:

```bash
git clone https://github.com/tavishitripathi/datascience_project_cancerdetect.git
cd Breast-Cancer-Detection
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook
```

Open the notebook file and run all cells.

---

## Conclusion

This project demonstrates how Machine Learning can be used for early detection of breast cancer. The Support Vector Machine algorithm provided high accuracy in classification of tumors as malignant or benign. Machine Learning can assist medical professionals in diagnosis and improve early detection systems.

---

## Future Improvements

* Try other algorithms (Random Forest, Logistic Regression, Neural Networks)
* Use deep learning with image datasets
* Deploy model as web application
* Add real-time prediction interface

---