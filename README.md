# OncoOrigin AI

**Clinical and Genomic-Summary Based Cancer Primary-Site Prediction**

## Overview
OncoOrigin AI is an experimental machine learning research prototype designed to predict likely primary cancer-site categories using clinical and genomic-summary features from the MSK-IMPACT dataset.

## Target Cancer Classes
- Lung
- Breast
- Prostate
- Pancreas
- Brain
- Uterus
- Ovary
- Colon
- Bladder
- Skin
- Soft Tissue
- Kidney
- Rectum
- Stomach
- Liver

## Technologies
- Python
- Pandas and NumPy
- Scikit-learn
- PyTorch
- CatBoost
- Gradio
- Google Colab

## Model Development
The project explores tabular machine learning and deep learning approaches, including a PyTorch multilayer perceptron and CatBoost benchmarking.

## Interface
The Gradio interface supports:
- Manual patient-feature input using dropdowns and numerical fields
- CSV-based batch predictions
- Top-five predicted classes and probabilities

## Disclaimer
This project is an experimental research prototype. It is not clinically validated and must not be used for cancer diagnosis or treatment decisions.

## Dataset
The project uses the MSK-IMPACT clinical/genomic-summary dataset. Follow the dataset provider's access, licensing, and redistribution requirements.
