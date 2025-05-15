# 🎵 Spotify Recommendation System  
## CSE303 Group Project | Recommendation System Using Neural Collaborative Filtering (NCF)

---

## 🚀 Project Overview  
This project presents a **data-driven music recommendation system** developed using **Spotify audio features**. By leveraging **machine learning models**, we aim to **predict song popularity**, understand **musical trends**, and deliver **personalized song recommendations**.

---

## 📊 Key Features

### 🧹 Data Preprocessing & Feature Engineering
- Cleaned and standardized Spotify’s audio dataset to ensure high-quality model input.
- Engineered temporal features (yearly & decade-wise) to support trend discovery and time-based analysis.

### 📈 Exploratory Data Analysis (EDA)
- Investigated core audio features: `danceability`, `energy`, `loudness`, and `popularity`.
- Visualized data using:
  - 📡 **Radar Charts**
  - 🔗 **Parallel Coordinates Plots**
  - 🗺️ **Geographic & Linguistic Trends**
- Identified genre-specific patterns and changes in audience preferences over time.

### 🤖 Machine Learning Models
- **Regression Models**:
  - Linear Regression  
  - Ridge & Lasso Regression  
  - Maximum Likelihood Estimation (MLE)  
  - Ordinary Least Squares (OLS)
- **Performance Metrics**:
  - R² Score  
  - Residual Trendlines
- **Model Tuning**:
  - Grid Search CV  
  - 5-Fold Cross-Validation

### 🔄 Recommendation Engine
- Tested collaborative filtering techniques:
  - ✅ **Singular Value Decomposition (SVD)**
  - ✅ **Neural Collaborative Filtering (NCF)** – achieved superior accuracy.
- Built a scalable and extendable system for future personalization.

---

## 🛠️ Technologies & Tools

| Category           | Tools Used                                              |
|--------------------|----------------------------------------------------------|
| **Programming**     | Python                                                   |
| **Libraries**       | `pandas`, `numpy`, `scikit-learn`, `statsmodels`        |
| **Visualization**   | `matplotlib`, `seaborn`, `plotly`                        |
| **ML Techniques**   | Regression, Collaborative Filtering, Grid Search CV      |

---

## 🎯 Project Outcome
- Delivered a prototype capable of **recommending popular songs** based on audio features.
- Gained **insights into long-term music trends**.
- Created a foundation for a **personalized music recommendation platform**.
- Useful for **artists**, **music producers**, and **analysts** to understand **audience dynamics**.

---

## 📌 Future Work
- Add user profiling for deeper personalization.
- Incorporate more diverse data sources (lyrics, streaming data).
- Integrate with real-time Spotify API.


