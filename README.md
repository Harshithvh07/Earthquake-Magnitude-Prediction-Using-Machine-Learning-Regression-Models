# **Earthquake Magnitude Prediction using Machine Learning**  

## **Overview**  
This project aims to predict earthquake magnitudes in India using machine learning regression techniques. We compare multiple models, including **Random Forest, Gradient Boosting, and Support Vector Regression (SVR)**, and visualize their performance.  

---

## **Dataset**  
The dataset contains information about past earthquakes in India, including:  
- **Latitude & Longitude** (Location)  
- **Depth** (in km)  
- **Magnitude**  
- **Other Seismic Parameters**  

**Target Variable:** Earthquake **Magnitude** (`mag`)  

---

## **Machine Learning Models Used**  
We trained and evaluated the following models:  

| Model               | MAE  | R² Score |
|---------------------|------|---------|
| **Random Forest**   | **0.150** | **0.680** |
| Gradient Boosting  | 0.164 | 0.650 |
| SVR (Support Vector) | 0.198 | 0.363 |

📌 **Random Forest performed the best**, explaining **68% of the variance** in earthquake magnitudes.  

---

## **Visualizations**  

### **1️⃣ Actual vs. Predicted Magnitude**  
Compares true vs. predicted magnitudes for each model.  
![](images/actual_vs_predicted.png)  

### **2️⃣ Residual Plot (Errors)**  
Shows the prediction errors (residuals) for each model.  
![](images/residual_plot.png)  

### **3️⃣ Feature Importance (RF & GB Models)**  
Identifies key features influencing magnitude prediction.  
![](images/feature_importance.png)  

---

## **Future Improvements**  
🚀 To enhance prediction accuracy, we can:  
- **Perform Hyperparameter Tuning** using `GridSearchCV`  
- **Experiment with Deep Learning (Neural Networks)**  
- **Try Advanced Models like LightGBM & CatBoost**  
- **Use More Features & Engineering Techniques**  

---

## **Contributors**  
- **Harshith** (harshithv07)  
- Open for collaborations! Feel free to fork & contribute. 🚀  

---
