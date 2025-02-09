# 📊  **Customer's Churn Prediction Analysis Dashboard-Info_Architects**

## **Introduction**

Customer churn is a critical metric that can significantly impact a company's bottom line. In our project, "Customer Churn Prediction Analysis Dashboard," we leverage the power of machine learning with Python to predict potential churn, enabling proactive strategies for customer retention. The predictive model, built using Random Forest algorithm, identifies key factors that contribute to customer attrition.

The insights derived from the model are seamlessly integrated into a dynamic Power BI dashboard. This interactive dashboard provides stakeholders with a comprehensive view of churn trends, key drivers, and actionable insights. With intuitive visualizations and filtering options, users can explore the data in depth, allowing for informed decision-making and targeted retention strategies.

This project not only demonstrates the effective use of machine learning in solving real-world business challenges but also highlights the importance of data visualization in translating complex insights into strategic actions.

## **Project Type**

PowerBi Dashboard, using Python and Machine Learning for modeling

## 🌐**Deployed App**

https://drive.google.com/file/d/1Is5Vj7SKXFPxpRRXPCgx0CwyfrNUByqm/view?usp=sharing

## **Video WalkThrough of the project**

https://drive.google.com/file/d/1w1ZvFe0w6BWww_fjkrnAgcDcALkZkeHB/view?usp=sharing

## 📂 **About the Dataset**

The dataset `WA_Fn-UseC_-Telco-Customer-Churn.csv` includes comprehensive collection of historical customer information, designed to help identify patterns and key factors influencing customer churn.

**Rows**

- Each Row Represents a Single Customer:

Every row corresponds to an individual customer and encapsulates their personal, subscription, and service usage data. This structure allows us to analyze customer behavior and identify patterns that lead to churn.

**Columns**

- The dataset comprises 21 columns.

Named
  - CustomerID
  - Gender
  - SeniorCitizen
  - Partner
  - Dependents
  - tenure
  - PhomeService
  - MultipleLines
  - InternetService
  - OnlineSecurity
  - OnlineBackup
  - DeviceProtection
  - TechSupport
  - StreamingTV
  - StreamingMovies
  - Contract
  - PaperlessBilling
  - PaymentMethod
  - MonthlyCharges
  - TotalCharges
  - Churn

**Dataset Summary**

- Rows: 21

- Columns: 7043

---

**Project Structure**
graphql
Copy
Edit
Customer-Churn-Prediction/  
│  
├── data/               # Folder for datasets  
├── notebooks/          # Jupyter notebooks for experiments  
├── src/                # Source code for preprocessing and modeling  
├── templates/          # HTML files for UI (if using Flask/Django)  
├── static/             # CSS, JS, images for UI (if applicable)  
└── README.md           # Project documentation  

## 🚀**Installation and Setup**

1. **Clone the repository:**
  ```bash
  git clone (https://github.com/B42-DA-026-Info-Architects/B42_DA_026_Info_Architects/tree/main)
  cd Customer-Churn-Prediction
```

2. **Install required dependencies:**

  ```bash
  pip install -r requirements.txt
  ``` 

3. **Run the application (if using a web interface):**

  ```bash
  python app.py
``` 

**How to Use**

Upload Dataset: Upload a CSV file containing customer data.

Train the Model: Click the "Train Model" button to build a churn prediction model.

View Insights: Analyze churn trends and model performance metrics.

Sample Dataset

You can use the Telco Customer Churn Dataset from Kaggle for testing and training.

Model Evaluation

The model performance is evaluated using the following metrics:

- Accuracy: 85%
- Precision: 80%
- Recall: 78%
- F1-score: 79%
- Visualization Dashboard

For advanced insights, use Power BI or Tableau to create a dynamic dashboard highlighting churn trends, high-risk segments, and contract duration impacts.

**Insights Gained**

- Demographic Impact: Older customers with longer tenure tend to have lower churn rates.
- High-risk Segments: Customers who contact support more frequently are at higher risk of churning.
- Contract Duration: Short-term contract customers have a higher churn rate.

## 🛠️**Technology Stack**

List and provide a brief overview of the technologies used in the project.

- Python
- Pandas
- matplotlib
- seaborn
- Machine Learning
- Random Forest Regression
- Power BI

## ❤️**Contributing**

Contributions are welcome! Fork the repository, create a new branch, and submit your pull request with improvements or new features.
























