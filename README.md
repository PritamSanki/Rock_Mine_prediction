# 🚀 SONAR Rock vs Mine Prediction using Machine Learning

A complete Machine Learning project that predicts whether an underwater object is a **Rock** or a **Mine** using SONAR signal data.  
This project is built using **Python**, **NumPy**, **Pandas**, and **Scikit-learn** with a Logistic Regression model.

---

# 📌 Project Overview

SONAR (Sound Navigation and Ranging) signals are used to detect underwater objects.  
This project uses a Machine Learning classification model to analyze SONAR data and determine whether the object detected is:

- 🪨 Rock
- 💣 Mine

The model is trained on the famous **SONAR dataset** and achieves impressive prediction accuracy.

---

# ✨ Features

✅ Data Collection & Preprocessing  
✅ Exploratory Data Analysis  
✅ Logistic Regression Model  
✅ Train-Test Split  
✅ Accuracy Evaluation  
✅ Confusion Matrix  
✅ Predictive System for Custom Input  
✅ Google Colab Compatible  
✅ Beginner-Friendly ML Project  

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| NumPy | Numerical Operations |
| Pandas | Data Handling |
| Matplotlib | Data Visualization |
| Scikit-learn | Machine Learning |
| Google Colab | Development Environment |

---

# 📂 Dataset Information

The dataset contains SONAR signals bounced off different surfaces.

- Total Rows: **208**
- Total Columns: **61**
- Features: **60 numerical attributes**
- Target Labels:
  - `R` → Rock
  - `M` → Mine

Dataset Source:
UCI Machine Learning Repository

---

# ⚙️ Machine Learning Workflow

## 1️⃣ Import Libraries

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import accuracy_score
