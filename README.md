# 🫀 ECG Rhythm Classification

### Python · Machine Learning · Multi-Class Classification · Macro-F1 Evaluation

[![Python](https://img.shields.io/badge/Python-3.x-blue)](#)
[![ML](https://img.shields.io/badge/Machine%20Learning-Classification-green)](#)
[![ECG](https://img.shields.io/badge/Signal-ECG%20Rhythm-red)](#)
[![Classes](https://img.shields.io/badge/Classes-11-purple)](#)
[![Metric](https://img.shields.io/badge/Evaluation-Macro--F1-orange)](#)

---

## 🔍 Overview

This project predicts **ECG rhythm categories** from extracted ECG measurement features using machine learning.

The goal is to classify each ECG record into one of multiple rhythm types, including normal rhythm and arrhythmias such as **Atrial Fibrillation**, **Sinus Tachycardia**, and **Atrial Flutter**.

---

## 🎯 Problem

Given ECG-derived patient records, the task is to predict the target label:

`Rhythm`

This is a **multi-class classification** problem with **11 rhythm categories**.

---

## ✅ Rhythm Classes

| Label | Rhythm Type |
|---|---|
| SB | Sinus Bradycardia |
| SR | Sinus Rhythm |
| AFIB | Atrial Fibrillation |
| ST | Sinus Tachycardia |
| AF | Atrial Flutter |
| SI | Sinus Irregularity |
| SVT | Supraventricular Tachycardia |
| AT | Atrial Tachycardia |
| AVNRT | Atrioventricular Node Reentrant Tachycardia |
| AVRT | Atrioventricular Reentrant Tachycardia |
| Other | Other rhythm category |

---

## ✨ What This Project Does

| Step | Description |
|---|---|
| Data Loading | Loads ECG feature data |
| Preprocessing | Handles missing values, numeric features, and encoded labels |
| Feature Engineering | Prepares ECG-derived measurements for modeling |
| Model Training | Trains ML classifiers for rhythm prediction |
| Evaluation | Uses Macro-F1 to evaluate class-balanced performance |
| Submission Output | Generates a Kaggle-ready `submission.csv` file |

---

## 🧪 Evaluation Metric

This project uses **Macro-F1** as the main evaluation metric.

Macro-F1 is useful because it gives equal importance to every rhythm class, including rare arrhythmia classes. That matters in medical-style classification because accuracy alone can hide poor performance on minority classes.

---

## 🛠️ Tech Stack

| Category | Tools / Methods |
|---|---|
| Language | Python |
| Environment | Jupyter Notebook |
| Task | Multi-Class Classification |
| Data Type | ECG-Derived Features |
| Evaluation | Macro-F1 |
| Output | `submission.csv` |

---

## 👩‍💻 My Role

I worked on this project with a focus on machine learning workflow development and classification evaluation.

My work included:

- loading and understanding ECG-derived feature data
- preprocessing numeric and categorical features
- preparing the target rhythm labels
- training classification models
- evaluating results using Macro-F1
- generating a submission file for prediction output

---

## ▶️ How to Run

1. Clone the repository.

`git clone https://github.com/SHREENITHI-TV/ECG-Rhythm-Classification.git`

2. Open the notebook.

`ecg_rhythm_classification.ipynb`

3. Install required Python libraries if needed.

`pip install pandas numpy scikit-learn matplotlib seaborn`

4. Run the notebook cells in order.

5. Review model evaluation results and generated output files.

---

## 📁 Repository Structure

| File | Purpose |
|---|---|
| `ecg_rhythm_classification.ipynb` | Main notebook for preprocessing, training, evaluation, and submission generation |
| `README.md` | Project documentation |

---

## 📌 Project Relevance

This project demonstrates practical experience with:

- machine learning classification
- healthcare-style data analysis
- ECG rhythm prediction
- multi-class model evaluation
- feature preprocessing
- Macro-F1 metric interpretation
- Kaggle-style submission workflow

---

## 🚀 Future Improvements

- Improve handling of rare rhythm classes
- Add feature importance analysis
- Tune classification models for better Macro-F1
- Package preprocessing and training into reusable Python scripts

---

<div align="center">

### Built to classify ECG rhythm patterns using machine learning and Macro-F1 based evaluation.

</div>
