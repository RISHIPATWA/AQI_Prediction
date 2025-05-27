# 🇮🇳 AQI Prediction in Indian Cities using KNN Regression

This project aims to predict the **Air Quality Index (AQI)** based on environmental pollutant data collected from various cities in India. It uses a **K-Nearest Neighbors (KNN) regression model** to make predictions and includes visualizations to help understand regional pollution levels.

---

## 📌 Objective

- Predict AQI using air pollutant features.
- Visualize regional pollution trends across Indian cities.
- Evaluate and analyze model performance.

---

## 🧠 Algorithm Used

- **K-Nearest Neighbors Regressor (KNN)**

### 🔍 Why KNN?

- Non-parametric and simple to implement.
- Effective for regression with real-valued features.
- Good at capturing similarity-based patterns in environmental data.

---

## 📊 Dataset Information

- **Name**: Air Quality Data in India
- **Source**: [Kaggle Dataset by Rohan Rao](https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india)
- **File Used**: `city_day.csv`
- **Attributes**:
  - Pollutants: `PM2.5`, `PM10`, `NO`, `NO2`, `NOx`, `CO`, `SO2`, `O3`, `NH3`, `Benzene`, `Toluene`, `Xylene`
  - Target: `AQI`
  - Categorical: `City`, `Date`

---

## 🧪 Features Used for Model

- **Input Features**:
  - PM2.5
  - PM10
  - NO
  - NO2
  - NOx
  - CO
  - SO2
  - O3
  - NH3
  - Benzene
  - Toluene
  - Xylene

- **Target Variable**:
  - AQI (Air Quality Index)

---

## 🧰 Tools and Libraries Used

- `pandas` for data handling
- `numpy` for numerical operations
- `matplotlib` and `seaborn` for visualizations
- `scikit-learn` for ML model and evaluation
- `Google Colab` for coding environment

---

## 📈 Model Evaluation

- Model: `KNeighborsRegressor(n_neighbors=5)`
- Evaluation Metrics:
  - R² Score (Train and Test)
  - Mean Squared Error (MSE)
- Visualization Plots:
  - AQI Distribution by City (Boxplot)
  - Actual vs Predicted AQI (Scatterplot)
  - Residuals Distribution (Histogram)

---

## 📊 Visual Insights

- **Boxplot**: Compares AQI values across cities.
- **Residual Plot**: Shows errors in predictions.
- **Scatter Plot**: Compares predicted AQI vs actual AQI.

---

## ✅ Project Results

- Successfully predicted AQI using pollutant levels.
- KNN provided a reasonable baseline for AQI regression.
- Visualizations highlighted city-wise pollution variations.

---

## 🚀 Future Work

- Add weather-based features like humidity, temperature, wind speed.
- Use more advanced models (e.g. Random Forest, XGBoost).
- Deploy the model in a web dashboard or mobile app.

---

## 👨‍💻 Author

Made with 💻 in **Google Colab**  
**Author**: *Your Name Here*

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
