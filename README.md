# Customer Churn Analysis

A data-driven project focused on understanding why customers leave a telecom service and identifying the strongest churn drivers. The analysis explores contract type, tenure, monthly charges, payment behavior, and service usage patterns to uncover the key reasons behind customer attrition.

## Overview

This project helps answer a core business question:

> Which customer behaviors and service characteristics are most associated with churn?

By combining exploratory data analysis and visual storytelling, the project highlights the risk patterns that matter most to retention teams and stakeholders.

## Project Objective

The goal of this work is to:

- analyze customer retention patterns,
- identify churn risk factors,
- visualize the most important trends,
- support business decisions aimed at reducing customer attrition.

---

## Dashboard Summary

The main insights from this analysis include:

- month-to-month contracts are strongly associated with churn,
- longer-tenure customers are more stable,
- higher monthly charges may increase churn risk,
- payment method and internet service type influence retention,
- senior citizens and some service patterns show elevated churn risk.

These findings create a practical dashboard-style summary for stakeholder review and customer retention planning.

---

## Dataset

This project uses the Telco Customer Churn dataset from the telecommunications domain.

### Key features

- Customer ID
- Gender
- Senior Citizen Status
- Partner / Dependents
- Tenure
- Phone Service
- Internet Service
- Contract Type
- Payment Method
- Monthly Charges
- Total Charges
- Churn Label

Data source: `data/Telco-Customer-Churn.csv`

---

## Key Visualizations

### 1. Churn Distribution

![Churn Distribution](./visuals/churn_distribution.png)

This chart shows the overall split between retained and churned customers.

### 2. Contract Type vs Churn

![Contract Type vs Churn](visuals/contract_vs_churn.png)

This visual helps reveal how contract length impacts customer retention.

### 3. Payment Method vs Churn

![Payment Method vs Churn](visuals/payment_method_churn.png)

This chart highlights whether certain payment methods correlate with churn.

### 4. Internet Service vs Churn

![Internet Service vs Churn](visuals/internet_service_churn.png)

This graphic shows churn differences by internet service category.

### 5. Monthly Charges Distribution

![Monthly Charges Distribution](visuals/monthly_charges_distribution.png)

This chart helps assess whether pricing or charge levels align with churn risk.

### 6. Senior Citizen vs Churn

![Senior Citizen vs Churn](visuals/senior_citizen_churn.png)

This view helps compare churn behavior for senior and non-senior customers.

### 7. Tenure Distribution

![Tenure Distribution](visuals/tenure_distribution.png)

This visualization shows how customer tenure relates to retention and churn outcomes.

---

## Repository Structure

```text
Customer_Churn_Analysis/
├── data/
│   └── Telco-Customer-Churn.csv
├── notebooks/
│   └── churn_analysis.ipynb
├── visuals/
│   ├── churn_distribution.png
│   ├── contract_vs_churn.png
│   ├── internet_service_churn.png
│   ├── monthly_charges_distribution.png
│   ├── payment_method_churn.png
│   ├── senior_citizen_churn.png
│   └── tenure_distribution.png
├── presentation/
├── reports/
├── sql/
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Tools and Libraries

This project was built with:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

See `requirements.txt` for the complete list of dependencies.

---

## Key Findings

- The churn rate is approximately **26.5%**.
- Customers on **month-to-month contracts** show the highest churn risk.
- Customers with **longer tenure** are significantly more likely to remain loyal.
- Higher monthly charges are associated with increased churn risk.
- Contract type is one of the strongest retention indicators in the dataset.
- Payment method and internet service category also reflect meaningful retention differences.

---

## How to Run

1. Create a Python environment.
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```bash
jupyter notebook notebooks/churn_analysis.ipynb
```

---

## Business Impact

This analysis can help customer success and retention teams:

- target high-risk accounts earlier,
- create smarter retention offers,
- improve contract design and pricing strategy,
- prioritize interventions for likely churn segments.

---

## License

This project is intended for educational and analytical use.

## Author

Customer Churn Analysis project
