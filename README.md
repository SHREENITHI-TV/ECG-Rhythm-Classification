# 🫀 ECG-Rhythm-Classification
[![Python](https://img.shields.io/badge/Python-3.x-blue)](#)
[![ML](https://img.shields.io/badge/Machine%20Learning-Classification-green)](#)
[![Metric](https://img.shields.io/badge/Evaluation-Macro--F1-orange)](#)

A machine learning classification project that predicts **one of 11 ECG/heart rhythm types** from extracted ECG measurements.  

---

## 📌 Problem Overview

Given ECG-derived features from **10,646 patients** (500 Hz sampling rate), the goal is to classify each record into one of **11 rhythm categories**, including normal rhythm and arrhythmias such as **Atrial Fibrillation (AFIB)** and **Sinus Tachycardia (ST)**.

**Target column:** `Rhythm`

---

## ✅ Classes (Rhythm Labels)

| Acronym | Full Name |
|--------|-----------|
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

---

## 🧪 Evaluation Metric (Macro-F1)

Evaluated using **Macro-F1**, which computes F1-score per class and averages them equally.  
This makes performance on minority/rare rhythm classes important.

---

## ✨ What This Project Does

- Loads and preprocesses ECG feature data
- Applies feature engineering (numeric transformations, handling missing values, encoding)
- Trains classification models for multi-class rhythm prediction
- Evaluates using Macro-F1 (and related classification metrics)
- Generates a Kaggle-ready `submission.csv`

