# BA-Project-Telco-Churn-Analysis
An end-to-end BA project analyzing customer churn, from requirements to a predictive model.

### Project Objective

This is an individual project completed to practice and demonstrate the fundamental skills of a Business Analyst. The goal was to follow an end-to-end data project lifecycle: from defining business requirements to delivering actionable insights from a predictive model.

**Business Problem:** A (hypothetical) Telco company is experiencing high customer churn.
**My Goal:** To identify *why* customers are leaving and build a model to predict *who* is at high risk of leaving next.

---

### Tools Used

* **Business Analysis:** Google Docs (for the BRD)
* **Data Analysis:** Python (Pandas)
* **Data Visualization:** Python (Matplotlib, Seaborn)
* **Machine Learning:** Python (Scikit-learn)

---

### Project Walkthrough & Key Deliverables

This repository is structured to follow the BA/Data project lifecycle:

#### 1. Phase 1: Business Requirements
* **File:** `BRD_Churn_Project.pdf`
* **Description:** A Business Requirements Document (BRD) defining the project's "why," including the business problem, objectives, stakeholders, and success metrics.

#### 2. Phase 2: Exploratory Data Analysis (EDA)
* **File:** `Telco_Churn_Analysis.ipynb` (see notebook for code)
* **Description:** I analyzed the raw data to find initial patterns.
* **Key Insight:** The EDA showed that churn is not random. It is heavily concentrated among new customers (low tenure) on Month-to-Month contracts.

![Churn by Contract](1_contract_churn.png)
![Churn by Tenure](4_tenure_churn.png)

#### 3. Phase 3: Predictive Modeling
* **File:** `Telco_Churn_Analysis.ipynb`
* **Description:** I cleaned the data and built a Decision Tree model to predict churn.
* **Result:** The model achieved **77.5% accuracy** and, more importantly, a **59% Recall** on the "Will Churn" class, making it a useful tool for targeting at-risk customers.

#### 4. Phase 4: Model Interpretation (Actionable Insights)
* **File:** `5_feature_importance.png` and `6_decision_tree.png`
* **Description:** I interpreted the model to find the *most important drivers* of churn.
* **Key Finding:** The model's decisions are based primarily on **Tenure** (44%) and **Internet Service (Fiber Optic)** (35%). This provides a clear, actionable focus for the business.

![Feature Importance](5_feature_importance.png)

---

### Final_Recommendation_Deck
summarize and the findings of entire project
