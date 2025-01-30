# 🏡 California Housing Price Prediction - Deep Learning (MLP)

## 📖 Project Overview
This project builds a **Multi-Layer Perceptron (MLP) regression model** using **TensorFlow/Keras** to predict **California housing prices** based on the **1990 U.S. Census dataset**.  
The model applies **data preprocessing, regularization, early stopping, and adaptive learning rate scheduling** to optimize training and prevent overfitting.

---

## 🚀 **Key Features**
✅ **Built a Fully Connected Neural Network (MLP)** with `TensorFlow/Keras`.  
✅ **Preprocessed data** with `StandardScaler` for feature normalization.  
✅ **Implemented EarlyStopping** to prevent overfitting (`patience=15`).  
✅ **Used Learning Rate Scheduler (`ReduceLROnPlateau`)** for adaptive training.  
✅ **Applied L2 regularization (`l2=0.01`) & Dropout (0.2)** for better generalization.  
✅ **Visualized Training & Validation Loss** using `Matplotlib`.  

---

## 📊 **Dataset: California Housing**
- The dataset contains **20640 samples** with **8 numerical features**.
- The target variable (`y`) represents **median house values (in $100,000s)**.

📌 **Features:**
| Feature       | Description |
|--------------|------------|
| `MedInc`     | Median income in the district |
| `HouseAge`   | Average house age in the district |
| `AveRooms`   | Average number of rooms per household |
| `AveBedrms`  | Average number of bedrooms per household |
| `Population` | Total population of the district |
| `AveOccup`   | Average number of occupants per household |
| `Latitude`   | Latitude coordinate of the district |
| `Longitude`  | Longitude coordinate of the district |
