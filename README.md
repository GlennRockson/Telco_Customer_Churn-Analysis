# Telco_Customer_Churn-Analysis
This is a Machine Learning Analysis on the rate of customer churn for a telco company

# Aim and Objective
The goal of this project is to develop a customer churn prediction model that can accurately identify customers at risk of churn. By being able to identify potential churners, businesses can implement targeted retention strategies to reduce customer attrition and improve overall customer satisfaction and profitability.
 

# Columns 💡

The dataset contained the following features:
* Gender -- Whether the customer is a male or a female
* SeniorCitizen -- Whether a customer is a senior citizen or not
* Partner -- Whether the customer has a partner or not (Yes, No)
* Dependents -- Customer has dependents or not (Yes, No)
* Tenure -- Number of months the customer has stayed with the company
* Phone Service -- Whether the customer has a phone service or not (Yes, No)
* MultipleLines -- Whether the customer has multiple lines or not
* InternetService -- Customer's internet service provider (DSL, Fiber Optic, No)
* OnlineSecurity -- Whether the customer has online security or not (Yes, No, No Internet)
* OnlineBackup -- Whether the customer has online backup or not (Yes, No, No Internet)
* DeviceProtection -- Whether the customer has device protection or not (Yes, No, No internet service)
* TechSupport -- Whether the customer has tech support or not (Yes, No, No internet)
* StreamingTV -- Whether the customer has streaming TV or not (Yes, No, No internet service)
* StreamingMovies -- Whether the customer has streaming movies or not (Yes, No, No Internet service)
* Contract -- The contract term of the customer (Month-to-Month, One year, Two year)
* PaperlessBilling -- Whether the customer has paperless billing or not (Yes, No)
* Payment Method -- The customer's payment method (Electronic check, mailed check, Bank transfer(automatic), Credit card(automatic))
* MonthlyCharges -- The amount charged to the customer monthly
* TotalCharges -- The total amount charged to the customer
* Churn -- Whether the customer churned or not (Yes or No)

# Data Preprocessing
* Used Simple Imputer using the median to Impute the missing values
* Used Simple Imputer (most frequent) and One Hot Encoder to encode the other remaining categorical columns
* Used SMOTE (Synthetic Minority Over-sampling Technique) to address class imbalance in target variable(Churn column).
* Used Robust scaler to normalize the dataset

# Modelling
 The following Models were trained:
* Logistic Regression
* Random Forest
* Gradient Boosting
* K-Nearest Neighbors
* XGBoost
* LightGBM
* catboost
* adaboost

# Final Model
Random Forest with an accuracy score of 86% and AUC score of 93% was selected. 
 
# Getting Started

1. **Clone the Repository:** `git clone [repository_url]`
2. **Install Dependencies:** `pip install -r requirements.txt`
3. **Run the Analysis Script:** `python analysis.py`

# Usage

- **Customize and Explore:** Tailor the analysis to your needs, and dive deep into the `notebooks` for in-depth insights.

# Join the Expedition ⚔️

# Contributions

Dare to be part of the adventure! Contribute and leave your mark on this epic journey:

1. **Fork the Repository.**
2. **Create a New Branch:** `git checkout -b feature_branch`
3. **Make Changes and Commit:** `git commit -m 'Add feature'`
4. **Push to the Branch:** `git push origin feature_branch`
5. **Submit a Pull Request.**

# Power BI Deployment
**Link** : https://app.powerbi.com/groups/me/reports/e5cba281-be07-48d3-96c1-07c401565b07/ReportSection?experience=power-bi

# Article on Medium
https://medium.com/@joojoakorful/indian-startup-ecosysyem-d2c359441172


##  Acknowledgements
Thanks to Azubi Africa and their instructors for guidng us through this journey.Special mention to Glen Anum,Rachel Appiah-Kubi and Portia Bentum.Also thanks to my team mates who helped in diverse way.Thanks to Sena Aku and Elisha Stanley.Thanks to my family and everyone who supported.



## License
This project operates under the [MIT License](LICENSE.md).

## Unlock Secrets 🧐

### Additional Information

For inquiries or deeper insights, contact our fearless explorer:

**Author:** Glenn Desmond Rockson  
**Email:** [joojoakorful@gmail.com]


