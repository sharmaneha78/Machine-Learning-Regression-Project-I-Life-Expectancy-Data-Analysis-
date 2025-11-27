# Machine-Learning-Regression-Project-I-Life-Expectancy-Data-Analysis-
A data analysis project that explores global life expectancy trends using health, economic, and demographic indicators. Includes full EDA, data preprocessing, statistical insights, visualizations, and factors influencing life expectancy across countries.
# 🌍 Life Expectancy Data Analysis & Prediction – Machine Learning Project

This project focuses on analyzing global **life expectancy** indicators and building a predictive machine learning model to understand which social, economic, and healthcare factors impact life expectancy worldwide. The project includes end-to-end data cleaning, visualization, feature engineering, and multiple predictive models.

---

## 🎯 Project Objective

- Analyze global patterns in life expectancy across countries and years.
- Identify the most important features influencing life span.
- Build a prediction model for estimating life expectancy based on key parameters.
- Provide insights & recommendations that support public health decisions.

---

## 📁 Dataset Overview

| Attribute | Description |
|-----------|------------|
| Country | Country Name |
| Year | Observation Year |
| Life_expectancy | Life expectancy in years |
| Adult_mortality | Probability of dying between ages 15–60 |
| Infant_deaths | Infant deaths per 1000 population |
| Alcohol | Alcohol consumption |
| Hepatitis_B | Immunization coverage |
| Measles | Measles cases |
| BMI | Body mass index |
| Under_five_deaths | Child mortality |
| Polio | Polio immunization |
| Total_expenditure | Total healthcare spending |
| Diphtheria | DTP immunization coverage |
| HIV/AIDS | Death rate from HIV |
| GDP | Gross Domestic Product |
| Population | Population count |
| Schooling | Years of schooling |
| ... | & other socio-economic features |

📊 **Dataset Shape:** (Rows × Columns)  
✔ Full statistical summary visualized & analyzed

---

## 🔧 Data Pre-processing & Cleaning

### Steps Performed
- Handling missing values (imputation / removal)
- Outlier treatment using visual inspection
- Encoding categorical values
- Feature scaling where needed
- Correlation analysis & multicollinearity check

---

## 📊 Exploratory Data Analysis (Key Insights)

| Observation | Insight |
|-------------|---------|
| Population vs Life Expectancy | Developing countries have lower life expectancy |
| Alcohol & schooling | Higher schooling & moderate alcohol linked to higher life span |
| Immunization | Countries with better vaccination programs live longer |
| HIV/AIDS | Major negative impact on life expectancy |
| GDP | Strong positive correlation with life expectancy |
| Adult mortality | Strong inverse relationship |

🔍 **Visualizations Included:**
- Univariate & distribution plots
- Pairwise relationship plots
- Heatmap correlation matrix
- Country-wise life expectancy trends

---

## 🧠 Feature Engineering

- Removed irrelevant / repeated / highly correlated features
- Created new health-impact parameters where necessary
- Standardization & normalization applied
- Converted categorical attributes into numerical

---

## 🤖 Model Training & Evaluation

### Models Used
- Linear Regression
- Random Forest Regressor
- XGBoost Regressor
- Decision Tree Regressor

### Performance Evaluation Metrics
- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- RMSE
- R² Score

📈 **Best Model Results :**
- Linear Regression R² : 0.78
- Random Forest R² : 0.92
- XGBoost R² : 0.94 (Best)
  
### Model Selection Conclusion
- **XGBoost shows highest prediction accuracy**
- Handles non-linear patterns & complex relationships effectively

---

## 🧾 Key Insights & Recommendations

| Insight | Recommendation |
|---------|--------------|
| Low schooling strongly reduces life expectancy | Increase education & literacy investment |
| High infant mortality & HIV levels | Public health programs & hospital access |
| Low GDP countries suffer shortest lifespan | Economic development essential |
| Vaccination improves life expectancy | Expand immunization programs |
| Healthcare expenditure strongly positive | Increase budget allocation |

---

## 🏁 Conclusion

- Socio-economic and healthcare development significantly influences life expectancy.
- **XGBoost** provides the best predictive performance.
- Data highlights global inequality and guides better policy decisions.
- Strong predictors include **GDP, schooling, immunization, HIV/AIDS, adult mortality**.

---

## 🚀 Future Work

- Deploy predictive model using Flask / Streamlit
- Geographic visualization using World Map charts
- Deep learning forecasting for future years
- Expand dataset with real-time WHO data

---

## 🛠 Tech Stack
| Category      | Tools                                                            |
| ------------- | -----------------------------------------------------------------|
| Language      | Python                                                           |
| Libraries     | Pandas, NumPy, Scikit-learn, Plotly,Matplotlib, Seaborn, XGBoost |
| Notebook      | Jupyter                                                          |
| Visualization | Seaborn & Matplotlib                                             |

## 👩‍💻 Project By: Neha Sharma
- Data Science | Machine Learning Enthusiast
