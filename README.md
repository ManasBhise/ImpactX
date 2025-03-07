# Air Quality Analysis and Prediction

![Project Banner](IMAGE_URL_HERE)

## Skills & Technologies Used

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-009688?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=for-the-badge&logo=python&logoColor=white)

## Project Overview
This project focuses on analyzing and predicting air quality levels based on historical pollution data. Using Exploratory Data Analysis (EDA) and Machine Learning models, the goal is to gain insights into key air pollutants and forecast PM2.5 levels.

## Dataset Used
- **Name:** Air Quality Data in India
- **Source:** Provided by the hackathon
- **Description:** Contains pollution levels (SO2, NO2, RSPM, SPM, PM2.5) across various locations in India.
- **Size:** 400,000+ records

## Exploratory Data Analysis (EDA)
The dataset was analyzed to:
- Identify missing values and outliers
- Visualize pollution trends over time
- Understand correlation between different pollutants
- Explore the most and least polluted locations

## Machine Learning Models Implemented
| Model                   | Mean Absolute Error | R² Score |
|-------------------------|--------------------|----------|
| Linear Regression       | 11.90              | 0.55     |
| Random Forest Regressor | 11.67              | 0.50     |
| XGBoost Regressor       | 10.94              | 0.54     |

XGBoost was the best-performing model based on R² Score.

## Project Setup & Execution

### Clone the Repository
```bash
git clone https://github.com/ManasBhise/air-quality-prediction.git
cd air-quality-prediction
