# Network Intrusion Detection using Machine Learning

## Overview

This project reproduces the first stage of the paper:

**Learning to Detect: A Data-Driven Approach for Network Intrusion Detection Using Machine Learning**

The objective is to classify network traffic into two classes:

- Normal
- Attack

using several supervised machine learning models together with an Autoencoder-based anomaly detection model.

## Dataset

The project uses the **NSL-KDD** dataset.

The dataset files are located in the `Dataset` folder.

## Implemented Models

- Decision Tree
- Random Forest
- Linear Support Vector Machine (LinearSVC)
- AdaBoost
- Gradient Boosting
- Multi-Layer Perceptron (MLP)
- Autoencoder

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Matthews Correlation Coefficient (MCC)

## Repository Structure

- `Dataset/`
- `Images/`
- `finalDatascienceproject.ipynb`
- `Report.pdf`
- `requirements.txt`

## Installation

Install the required libraries:

```bash
pip install -r requirements.txt
```

Then open the notebook using Jupyter Notebook or Google Colab.
## Running the Project

The complete experiment is available in two formats:

- `finalDatascienceproject.ipynb` – Jupyter Notebook version.
- `src/datascienceproject.py` – Python script version that runs the full experiment.

Install the required packages:

```bash
pip install -r requirements.txt
```

Run the script:

```bash
python src/datascienceproject.py
```
## Author

Sewar Halifa
