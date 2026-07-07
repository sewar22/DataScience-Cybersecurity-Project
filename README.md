# Network Intrusion Detection using Machine Learning

## Overview

This project is based on the paper:

**Learning to Detect: A Data-Driven Approach for Network Intrusion Detection Using Machine Learning**

The project not only reproduces the first stage of the methodology presented in the paper for binary network intrusion detection, but also provides an independent implementation, comprehensive exploratory data analysis (EDA), feature engineering analysis, critical evaluation of the paper, reproducibility analysis, hyperparameter optimization, extensive experimental evaluation, and a comparative analysis of multiple machine learning models using several evaluation metrics.

The objective of this project is to classify network traffic into two classes (**Normal** and **Attack**) using several supervised machine learning models together with an Autoencoder-based anomaly detection model.

---

## Dataset

This project uses the **NSL-KDD** dataset, a widely used benchmark dataset for intrusion detection research.

The dataset files are located in the **Dataset** folder.

---

## Implemented Models

The following machine learning models were implemented and evaluated:

- Decision Tree
- Random Forest
- Linear Support Vector Machine (LinearSVC)
- AdaBoost
- Gradient Boosting
- Multi-Layer Perceptron (MLP)
- Autoencoder

---

## Evaluation Metrics

The models were evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Matthews Correlation Coefficient (MCC)

---

## Repository Structure

```
DataScience-Cybersecurity-Project
│
├── Dataset/
├── Images/
├── src/
│   └── datascienceproject.py
├── Datascienceprojectfinalversion.ipynb
├── Report.pdf
├── README.md
└── requirements.txt
```

---

## Installation

Install the required Python packages:

```bash
pip install -r requirements.txt
```

---

## Running the Project

The project is available in two formats:

### Jupyter Notebook

Open:

```
Datascienceprojectfinalversion.ipynb
```

using **Google Colab** or **Jupyter Notebook**.

### Python Script

Run:

```bash
python src/datascienceproject.py
```

---

## Experimental Results

The project includes:

- Complete exploratory data analysis (EDA)
- Data preprocessing
- Feature engineering
- Hyperparameter optimization
- Training of seven machine learning models
- Autoencoder-based anomaly detection
- Confusion matrices
- Performance comparison
- Error analysis
- Critical evaluation of the selected paper
- Reproducibility analysis
- Final conclusions

Among all evaluated models, the **Autoencoder** achieved the best overall performance, obtaining the highest Accuracy, Recall, F1-score, and Matthews Correlation Coefficient (MCC), demonstrating the effectiveness of reconstruction-based anomaly detection for binary network intrusion detection.

---

## Project Report

The complete report is provided in:

```
Report.pdf
```

The report includes:

- Summary of the selected paper
- Critical Evaluation
- Feature Engineering Analysis
- Reproducibility Analysis
- Experimental Results
- Conclusions

---

## Requirements

Main libraries used in this project:

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras

---

## Author

**Sewar Halifa**

Computer Science Student
