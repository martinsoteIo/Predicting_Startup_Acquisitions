# 🔍 Predicting Startup Acquisitions using Crunchbase Data

This repository contains the work for a final Machine Learning project focused on solving a **binary imbalanced classification problem** using real-world data from Crunchbase.

---

## 🎯 Objective

The main objective is to predict whether a startup will be **acquired** based on its historical investment and company data.

To achieve this, we reformulate the task as a **binary classification problem**:

- `1`: The startup was acquired (`status == "acquired"`)
- `0`: The startup was not acquired (e.g. `operating`, `closed`, `ipo`, etc.)

The classification task is clearly **imbalanced**, with the acquired startups representing a small portion of the dataset.

---

## 🤖 Motivation and Evaluation

This project simulates the perspective of a **potential investor or buyer** interested in identifying startups with high chances of acquisition.

From this point of view, it is **crucial to avoid false positives**, i.e., predicting that a startup will be acquired when it won’t be. Therefore, the **primary evaluation metric** for this problem will be:

- ✅ **Precision**

Other metrics (F1-score, balanced accuracy, AUC) may also be considered for comparison purposes.

---

## 📦 Dataset

- **Source**: [Kaggle - Startup Investments Crunchbase](https://www.kaggle.com/datasets/arindam235/startup-investments-crunchbase/data)
- **File used**: `investments_VC.csv`

The dataset includes variables such as:

- Startup name and category
- Country code
- Total funding received
- Number of funding rounds
- Status (acquired, operating, closed, ipo…)
- Founding and funding dates

These features offer a rich base for modeling startup success and acquisition likelihood.

---

## 🧩 Project Scope

In the coming stages of this project, we aim to:

1. Explore and clean the dataset
2. Engineer relevant features
3. Handle class imbalance
4. Train classification models
5. Evaluate using precision-focused metrics
6. Interpret and analyze the model results

---

## 👥 Team

- Samuel Clemos Gómara
- Martín Orenes Peñas  
- Martín Sotelo Aguirre
 
---

## 📄 License
This project is licensed under the **MIT License**. See the `LICENSE` file for details.
