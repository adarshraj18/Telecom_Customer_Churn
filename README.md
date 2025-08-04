# **Telecom Customer Churn: EDA & Retention Strategy (SQL + Python)**  

## **About the Dataset**  
This project uses the **Telco Customer Churn** dataset from IBM, designed to help telecom providers understand and address customer attrition. Each row represents a customer, and each column captures behavioral, demographic, and account-related attributes.  

**Why It Matters:**  
For subscription-based businesses, **churn directly impacts profitability**. Acquiring a new customer costs **5–7x more** than retaining an existing one. By identifying churn drivers, telecom providers can design **focused retention programs** that improve **Customer Lifetime Value (CLV)** and **reduce revenue volatility**.  

**Data Includes:**  
- **Churn Indicator** – Whether a customer left in the last month.  
- **Services Signed Up For** – Phone, multiple lines, internet, online security, online backup, device protection, tech support, streaming TV and movies.  
- **Account Info** – Tenure, contract type, payment method, paperless billing, monthly charges, total charges.  
- **Demographics** – Gender, age range, partners, dependents.  

**Source:** [IBM Telco Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

---

## **1. Objective**  
To **explore patterns in customer churn** using SQL and Python, and answer key business questions:  
1. Which customers are most likely to churn, and why?  
2. How do **contracts, payment methods, tenure, service types, and demographics** influence churn?  
3. What actionable strategies can reduce churn and improve retention?  

---

## **2. Approach & Methodology**  
- **Data Cleaning & Preparation:**  
  - Handled missing values (e.g., total charges for new customers).  
  - Encoded categorical variables for meaningful grouping.  
  - Segmented customers based on tenure, contract type, and services.  

- **Exploratory Data Analysis (EDA):**  
  - Used **SQL** for aggregations, cohort segmentation, and churn rate calculations.  
  - Used **Python** for trend analysis and percentage-based breakdowns.  
  - Conducted **correlation checks** to identify relationships between attributes and churn.  

- **Key Techniques:**  
  - Group By and Join operations for customer segmentation.  
  - Cohort analysis to study churn by tenure.  
  - Comparative percentage analysis for payment methods and contracts.

---

## **3. Key Insights & Findings**  

### **3.1 Contract Type and Churn**  
- **42% churn** for month-to-month customers vs **3%** for two-year contracts.  
- Month-to-month customers have **14x higher churn**, indicating they are the most “at risk.”  
**Business Implication:** Incentivizing long-term contracts could drastically **stabilize revenue**.

---

### **3.2 Payment Methods and Churn**  
- **45% churn** among electronic check users vs **15–18%** among credit card/bank transfer users.  
**Business Implication:** Trust, convenience, or fraud concerns with electronic checks may be driving attrition. Payment migration campaigns can reduce churn.

---

### **3.3 Churn by Tenure**  
- **50% churn** for customers in their first year vs **15%** for those with >3 years tenure.  
**Business Implication:** The **first year is critical**. Loyalty programs and onboarding support can significantly improve retention.

---

### **3.4 Churn by Internet Service Type**  
- **30% churn** for Fiber Optic users vs **20%** for DSL users.  
**Business Implication:** Service reliability and pricing for Fiber Optic need attention to protect market share.

---

### **3.5 Senior Citizens and Churn**  
- **41% churn** among senior citizens vs **26%** among non-seniors.  
**Business Implication:** Dedicated customer support and simplified plans can help retain senior customers.

---

## **4. Visual & Analytical Insights**  
- **Churn by Payment Method:** Bar charts show electronic check users are **3x more likely to churn**.  
- **Cohort Analysis by Tenure:** Line graphs depict a **sharp decline in churn** after year one.  
- **Contract Type Visualization:** Month-to-month contracts dominate churn volume, while long-term contracts create a **protective effect**.

---

## **5. Recommendations**  
1. **Promote Long-Term Contracts:** Offer discounts, bundles, and loyalty perks to shift customers from month-to-month to annual/bi-annual plans.  
2. **Address Payment Trust Issues:** Educate customers on secure methods and incentivize credit card/bank transfer usage.  
3. **Enhance Early Engagement:** Implement onboarding campaigns, targeted offers, and satisfaction surveys within the first 90 days.  
4. **Senior-Centric Programs:** Provide simplified services and dedicated support lines for senior citizens.  
5. **Optimize Fiber Optic Experience:** Invest in quality improvements and transparent pricing to boost satisfaction.

---

## **6. Tools & Skills Used**  
- **SQL:** Aggregations, joins, churn segmentation, cohort analysis.  
- **Python:** Exploratory Data Analysis, percentage-based churn metrics, and trend breakdowns.  
- **Analytics:** KPI design, customer segmentation, and retention modeling.

---

## **7. Future Work**  
- Develop **predictive churn models** using classification algorithms.  
- Perform **customer lifetime value (CLV)** analysis to prioritize high-value segments.  
- Run **A/B testing** to measure the impact of retention campaigns.

---

## **8. Conclusion**  
Churn at Telecom is driven by **contract flexibility, payment trust, early tenure challenges, and demographic factors**. By addressing these areas, the company could **reduce churn by 20–30%**, leading to **higher customer lifetime value** and **sustainable revenue growth**.
