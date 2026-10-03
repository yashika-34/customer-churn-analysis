# Customer Churn Analysis

A data-driven project focused on understanding why customers leave a telecom service and identifying the strongest churn drivers. The analysis uses a customer churn dataset to explore contract type, tenure, monthly charges, payment behavior, and service usage patterns.

## Project Objective

The goal of this project is to:

* Analyze customer retention patterns
* Identify risk factors associated with churn
* Visualize key trends and customer segments
* Support business decisions for reducing customer attrition

---

## Dashboard Summary

This churn analysis highlights the most important business signals behind customer exits:

* Month-to-month contracts are strongly associated with churn
* Longer-tenure customers are more stable
* Higher monthly charges may contribute to customer dissatisfaction
* Payment methods and internet services can influence customer retention
* Senior citizens and certain service combinations show elevated churn risk

The project is structured to provide both a data narrative and a visual dashboard-style summary for stakeholder review.

---

## Dataset

The project uses the Telco Customer Churn dataset from the telecommunications domain.

### Key Features

* Customer ID
* Gender
* Senior Citizen Status
* Partner / Dependents
* Tenure
* Phone Service
* Internet Service
* Contract Type
* Payment Method
* Monthly Charges
* Total Charges
* Churn Label

**Dataset Source:** `data/Telco-Customer-Churn.csv`

---
## Key Visualizations

### 1. Churn Distribution

![Churn Distribution](./visuals/churn_distribution.png)

---

### 2. Contract Type vs Churn

![Contract Type vs Churn](./visuals/contract_vs_churn.png)

---

### 3. Payment Method vs Churn

![Payment Method vs Churn](./visuals/payment_method_churn.png)

---

### 4. Internet Service vs Churn

![Internet Service vs Churn](./visuals/internet_service_churn.png)

---

### 5. Monthly Charges Distribution

![Monthly Charges Distribution](./visuals/monthly_charges_distribution.png)

---

### 6. Senior Citizen vs Churn

![Senior Citizen vs Churn](./visuals/senior_citizen_churn.png)

---

### 7. Tenure Distribution

![Tenure Distribution](./visuals/tenure_distribution.png)

## Repository Structure

```text
Customer_Churn_Analysis/
│
├── data/
│   └── Telco-Customer-Churn.csv
│
├── notebooks/
│   └── churn_analysis.ipynb
│
├── visuals/
│   ├── churn_distribution.png
│   ├── contract_vs_churn.png
│   ├── internet_service_churn.png
│   ├── monthly_charges_distribution.png
│   ├── payment_method_churn.png
│   ├── senior_citizen_churn.png
│   └── tenure_distribution.png
│
├── presentation/
├── reports/
├── sql/
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Tools and Libraries

This project was built using:

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

See `requirements.txt` for the complete dependency list.

---

## Key Findings

* Overall churn rate is approximately **26.5%**
* Customers with **month-to-month contracts** show the highest churn rate
* Customers with **longer tenure** are significantly more likely to stay
* Higher monthly charges are associated with increased churn risk
* Contract type is one of the str
