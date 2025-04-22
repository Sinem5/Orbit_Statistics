# 🛰️ Orbital Decay Time Prediction
This repository contains a complete workflow for exploring, analyzing, and predicting the decay time of satellites in orbit using data science techniques. The project is divided into three main notebooks: Exploratory Data Analysis (EDA), Descriptive Analysis, and Machine Learning-based Prediction.

## 📁 Project Structure
### 1_EDA.ipynb - Exploratory Data Analysis
This notebook covers:

- Data loading and initial inspection

- Handling of missing values and outliers

- Type conversions and feature categorization

- Initial insights into orbital parameters and decay times

### 2_Descriptive_Analysis.ipynb - Descriptive Analysis
In this stage:

- Distributions and statistical summaries are explored

- Relationships between features are visualized

- Correlations, scatter plots, and boxplots are used to understand feature importance

- Variance Inflation Factor (VIF) is computed to detect multicollinearity between numerical features

- Principal Component Analysis (PCA) is performed to reduce dimensionality and visualize the main sources of variance in the dataset

- Highlights trends affecting orbital decay (e.g., altitude, inclination)

### 3_Orbital_Decay_Time_Prediction.ipynb - Predictive Modeling
This final notebook includes:

- Feature selection and preprocessing

- Model training using machine learning regressors

- Evaluation using metrics like MAE and RMSE

- Interpretation of results and future considerations


## 📈 Key Insights
- Certain orbital parameters such as altitude and eccentricity have strong effects on decay time.

- A regression model can effectively estimate decay duration based on selected features.

- Proper data cleaning and understanding of physical principles are critical in modeling orbital phenomena.

## 🚀 Future Work
- Integrating physics-based models with machine learning

- Exploring time-series approaches


## 🧠 Author
Sinem Çelik </br>
Passionate about space, computer vision, and robotics </br>
[LinkedIn](https://www.linkedin.com/in/sinem-celik-dl/) | [GitHub](https://github.com/Sinem5)