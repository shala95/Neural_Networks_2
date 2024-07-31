# Neural_Networks_2
# Disease Classification using Deep Learning

## Table of Contents

Introduction
Team Members
Project Structure
Setup and Installation
Data Preparation
Exploratory Data Analysis (EDA)
Model Training and Evaluation
Ensembling
Self-Supervised Learning
Results
Contributions
Acknowledgments
Introduction

This project involves the classification of healthy and unhealthy leaf images using various deep learning techniques. The work includes extensive data preprocessing, exploratory data analysis, model training with data augmentation, and the use of transfer learning and ensembling methods to improve classification accuracy.

## Team Members

Mohammad Amiri (10887256)
Sara Limooee (100886949)
Dorsa Moadeli (10926114)
Mohamed Shoala (10871548)

## Project Structure

EDA-2.ipynb: Notebook containing the Exploratory Data Analysis.
Baseline_models-2.ipynb: Notebook for training baseline models.
Transfer_Learning.ipynb: Notebook for implementing transfer learning.
ENSAMBLING.ipynb: Notebook for ensembling models.
HW#1_report-2.pdf: Project report detailing methodology and results.

## Setup and Installation

### Clone the repository:
```
git clone <repository_url>
cd <repository_directory>
```
Create and activate a virtual environment:
```
python3 -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate
````
Install the required packages:
```
pip install -r requirements.txt
Data Preparation
```
The dataset consists of leaf images categorized into healthy and unhealthy. Initial data preprocessing includes:

Removal of outliers and duplicates using OpenCV-2.
Partitioning data into training and test sets with a 60-40 distribution.
Exploratory Data Analysis (EDA)

EDA was conducted to understand the dataset distribution and identify potential issues such as imbalance and outliers. Details are available in EDA-2.ipynb.

## Model Training and Evaluation

Several models were trained and evaluated, including:

Simple Convolutional Neural Network (CNN)
Transfer learning models such as MobileNetV2, EfficientNetB0, and Xception
Data augmentation techniques like Random Brightness and Random Translation were applied to the training data to prevent overfitting.

## Ensembling

Ensembling involved training multiple models and combining their predictions to improve accuracy. Methods included:

Simple whole dataset training
KFold cross-validation
Resampling
Self-Supervised Learning

Self-supervised learning was attempted using the SIMCLR method to enhance model performance by leveraging contrastive learning.

## Results

The best performing models and their accuracies are documented in the project report HW#1_report-2.pdf. The final ensemble model achieved an accuracy of 79% in local testing and 75% on the server.

## Contributions

Dorsa and Mohamed: Data refinement and EDA
Mohammad: Outlier detection and initial model definitions
Sara: Data augmentation and model experiments
Collective Effort: Model fine-tuning and report preparation

## Acknowledgments

We acknowledge the guidance and support provided by our course instructors at Politecnico di Milano.

