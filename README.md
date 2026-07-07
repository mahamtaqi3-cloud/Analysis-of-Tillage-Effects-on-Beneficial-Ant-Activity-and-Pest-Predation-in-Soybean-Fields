# 🌱 Analysis-of-Tillage-Effects-on-Beneficial-Ant-Activity-and-Pest-Predation-in-Soybean-Fields

> **Using Machine Learning to Explore Sustainable Agriculture and Biological Pest Control**

---

## 📖 Project Overview

Beneficial insects play a vital role in sustainable agriculture by naturally suppressing crop pests. Agricultural management practices, such as **tillage**, can influence ant abundance, species diversity, and the effectiveness of biological pest control.

This project analyzes a real-world ecological dataset to investigate how **tillage practices**, **environmental conditions**, and **ant communities** affect **egg predation rates** in agricultural fields. Using **Python**, **Exploratory Data Analysis (EDA)**, and a **Random Forest Regression** model, we identify the environmental and biological factors that contribute to natural pest control.

---

## 🎯 Objectives

- 📊 Explore ecological field data from agricultural experiments.
- 🐜 Analyze the relationship between tillage practices and beneficial ant activity.
- 🌾 Investigate environmental factors affecting biological pest control.
- 🤖 Build a Random Forest Regression model to predict egg predation rates.
- 📈 Identify the most influential variables using feature importance analysis.

---

## 📂 Dataset

This project uses a **real ecological field dataset** from an agricultural tillage experiment containing:

- Crop type
- Tillage treatment
- Air, ground, and soil temperatures
- Humidity
- Ant abundance
- Species richness
- Individual ant species counts
- Egg predation measurements

### Key Variables

| Variable | Description |
|----------|-------------|
| Crop | Agricultural crop (Corn/Soybean) |
| Treatment | Tillage practice |
| Air_Temperature | Air temperature |
| Soil_Temperature | Soil temperature |
| Humidity | Relative humidity |
| Abundance | Total ant abundance |
| Richness | Number of ant species |
| Proportion_Eaten | Egg predation rate (Target Variable) |

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Kaggle Notebook

---

## 🔬 Project Workflow

### 1️⃣ Data Loading
- Import dataset
- Inspect dataset structure

### 2️⃣ Data Cleaning
- Handle missing values
- Remove duplicates
- Encode categorical variables

### 3️⃣ Exploratory Data Analysis (EDA)
- Distribution of egg predation
- Ant abundance analysis
- Species richness analysis
- Comparison of tillage treatments
- Crop-wise comparisons
- Correlation heatmap
- Scatter plots

### 4️⃣ Machine Learning
- Feature selection
- Train-test split
- Random Forest Regression
- Model prediction

### 5️⃣ Model Evaluation
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score
- Feature Importance
- Actual vs Predicted visualization

---

## 📈 Model Performance

| Metric | Score |
|---------|------:|
| **MAE** | **0.298** |
| **RMSE** | **0.360** |
| **R² Score** | **0.141** |

---

## 📊 Visualizations

The project includes:

- 📌 Egg Predation Distribution
- 📌 Tillage Treatment Comparison
- 📌 Crop Comparison
- 📌 Ant Abundance Distribution
- 📌 Species Richness Distribution
- 📌 Correlation Heatmap
- 📌 Ant Abundance vs Predation Scatter Plot
- 📌 Feature Importance Chart
- 📌 Actual vs Predicted Plot

---

## 🔍 Key Findings

- 🌱 Tillage practices influence biological pest control efficiency.
- 🐜 Ant abundance contributes to egg predation.
- 🌡 Environmental conditions affect predator activity.
- 🌾 Species richness varies across agricultural treatments.
- 🤖 Machine learning identifies the most influential ecological variables associated with predation.

---

## 📁 Project Structure

```
📦 Impact-of-Tillage-Practices
│
├── data/
│   └── ecological_dataset.csv
│
├── notebook.ipynb
├── README.md
├── requirements.txt
└── images/
```

---

## 🚀 Future Improvements

- Include rainfall and soil moisture variables.
- Compare multiple machine learning models.
- Perform hyperparameter tuning.
- Analyze seasonal trends in predator activity.
- Develop classification models for predation categories.

---

## 💡 Biological Significance

Understanding how agricultural practices influence beneficial insect communities helps improve **Integrated Pest Management (IPM)** strategies and promotes more sustainable farming systems by reducing reliance on chemical pesticides.

---

## 👩‍💻 Author

**Maham Taqi**



## ⭐ If you found this project helpful, consider giving it a star!
````
