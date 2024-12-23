# Poverty Solutions Project

This project explores poverty trends across selected countries and employs machine learning models to predict future poverty levels. It concludes with actionable recommendations to combat poverty in alignment with sustainable development goals.

---

## **1. Project Overview**

- **Objective**: Analyze global poverty trends and predict future levels to recommend targeted poverty reduction strategies.
- **Countries Analyzed**: Brazil, Egypt, Pakistan, Turkey, United States.
- **Data Source**: Global Poverty Indicators Dataset (1990–2010).

  

Our project supports the following Sustainable Development Goals (SDGs):

<p align="center">
    <img src="https://github.com/user-attachments/assets/2cb7dc91-ac54-4c6d-b509-2692a4b503bb" alt="9" width="20%">
    <img src="https://github.com/user-attachments/assets/dbc424a6-8568-450b-a7cc-3ad02cf414d5" alt="11" width="20%">
    <img src="https://github.com/user-attachments/assets/febf118a-76c4-4bde-84e2-1d91d1b57eff" alt="12" width="20%">
</p>


---

## **2. Data Processing**

### **Steps**:
1. **Data Import**: Imported data from a CSV file.
2. **Column Selection**: Filtered relevant columns: `Entity`, `Code`, `Year`, `$2.15 a day - Share of population in poverty`.
3. **Target Countries**: Focused on five countries of interest: `Brazil`, `Egypt`, `Pakistan`, `Turkey`, `United States`.
4. **Visualization**: Displayed trends and comparisons using pie charts and bar charts.

---

## **3. Machine Learning Models**

### **Model 1: Decision Tree Regressor**
- **Accuracy**: 97.22%
- **Metrics**:
  - Mean Squared Error (MSE): 1.98
  - Root Mean Squared Error (RMSE): 1.41
  - R-Squared: 0.97
- **Performance**: The most accurate model for poverty prediction.

### **Model 2: Pipeline Model**
- **Accuracy**: 53.85%
- **Metrics**:
  - MSE: 32.87
  - RMSE: 5.73
  - R-Squared: 0.54
- **Limitation**: Less effective for complex datasets.

### **Model 3: Linear Regression**
- **Accuracy**: 38.31%
- **Metrics**:
  - MSE: 43.93
  - RMSE: 6.63
  - R-Squared: 0.38
- **Limitation**: Poor prediction performance.

### **Model Comparison**
| Model Name            | Accuracy (%) |
|-----------------------|--------------|
| Decision Tree         | 97.22        |
| Pipeline Model        | 53.85        |
| Linear Regression     | 38.31        |

---

## **4. Recommendations for Poverty Reduction**

### **Country-Specific Recommendations**
| Country          | Recommendations                    | Expected Impact |
|-------------------|------------------------------------|-----------------|
| Brazil           | Social Protection Programs         | High            |
| Brazil           | Invest in Education                | High            |
| Brazil           | Job Creation                       | Medium          |
| Pakistan         | Microfinance Initiatives           | High            |
| Pakistan         | Agricultural Support               | Medium          |
| Pakistan         | Health Services                    | High            |
| United States    | Minimum Wage Increase              | Medium          |
| United States    | Affordable Housing                 | High            |
| United States    | Healthcare Access                  | High            |
| Egypt            | Economic Diversification           | Medium          |
| Egypt            | Women’s Empowerment                | Medium          |
| Egypt            | Education and Training             | High            |
| Turkey           | Social Safety Nets                 | High            |
| Turkey           | Economic Reforms                   | High            |
| Turkey           | Rural Development                  | Medium          |

### **Visualization**:
- **Heatmap**: Displays recommendations and their expected impact across countries.

---

## **5. Conclusion**

- **Best Model**: The Decision Tree Regressor demonstrated the highest accuracy for poverty prediction.
- **Actionable Insights**: Recommendations tailored to specific countries have the potential to significantly reduce poverty levels.
- **Alignment with SDG 1**: These efforts contribute to the Sustainable Development Goal of eradicating poverty.
