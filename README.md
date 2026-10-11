<div align="center">

# 🚗 Used Vehicle Valuation Engine

An end-to-end Machine Learning regression pipeline built in Google Colab to predict secondary market vehicle valuations based on specifications, mileage, brand equity, and depreciation profiles.

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AbdullahAmir1562003/Used-Vehicle-Valuation-Engine/blob/main/Used_Vehicle_Valuation_Engine.ipynb)

</div>

---

### 📌 Project Overview

Valuing pre-owned vehicles is complex due to non-linear depreciation factors, odometer wear, fuel economy trends, and localized brand dynamics. This project formulates a data-driven valuation engine using predictive modeling to generate accurate market estimates for buyers, sellers, and auto-dealers.

---

### 🌟 Key Workflow & Pipeline

1. **Exploratory Data Analysis (EDA):** Feature distribution checks, skewness detection, correlation matrix heatmaps, and price-outlier pruning.
2. **Data Preprocessing & Cleaning:**
   - Imputation for missing mechanical and odometer values.
   - Categorical transformation via Target Encoding / One-Hot Encoding for categorical features (brand, body type, fuel type, transmission).
   - Numerical scaling and feature normalization.
3. **Feature Engineering:** Extracted vehicle age ratios, annual mileage rates, and depreciation tiers.
4. **Model Development & Benchmarking:**
   - Evaluated candidate regression models (e.g., Linear Regression, Ridge, Random Forest Regressor, and Gradient Boosting).
   - Hyperparameter fine-tuning via Cross-Validation (`GridSearchCV` / `RandomizedSearchCV`).
5. **Evaluation Metrics:** Evaluated performance via **R² Score**, **Mean Absolute Error (MAE)**, and **Root Mean Squared Error (RMSE)**.

---

### 🛠️ Tech Stack & Dependencies

- **Runtime & Environment:** Google Colab / Jupyter Notebook
- **Language:** Python
- **Data Engineering:** `pandas`, `numpy`
- **Visualization:** `matplotlib`, `seaborn`
- **Machine Learning:** `scikit-learn`

---

### 🚀 Getting Started

#### Option 1: Run Instantly on Google Colab (Recommended)
Click the badge below to run the interactive notebook with pre-installed GPU/CPU acceleration:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AbdullahAmir1562003/Used-Vehicle-Valuation-Engine/blob/main/Used_Vehicle_Valuation_Engine.ipynb)

 #### Option 2: Run Locally
 
 1. **Clone the repository:**
    ```bash
    git clone https://github.com/AbdullahAmir1562003/Used-Vehicle-Valuation-Engine.git
    cd Used-Vehicle-Valuation-Engine

 2. **Set up a virtual environment (Optional):**
    ```bash
   python -m venv venv
   # Windows:
  venv\Scripts\activate
   # macOS/Linux:
    source venv/bin/activate
  
    3. **Install dependencies & run:**
   ```bash
    pip install numpy pandas scikit-learn matplotlib seaborn jupyter
    jupyter notebook Used_Vehicle_Valuation_Engine.ipynb
