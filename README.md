# **Telecom Customer Churn Analysis**  

## **1. Project Description**  

### **Introduction**  
Customer churn is a major challenge for businesses, especially in competitive industries like telecommunications. This project analyzes customer data to identify churn drivers, predict high-risk customers, and recommend retention strategies.  

### **About the Company**  
A leading telecommunications provider offering mobile and internet services, catering to both individual and business customers.  

### **Objectives of the Report**  
- Identify key factors driving customer churn.  
- Analyze high-risk customer segments and suggest retention strategies.  
- Predict new customers likely to churn for proactive intervention.  
- Provide marketing insights based on churn trends.  

---

## **2. Project Workflow**  
- **Step 1:** ETL Process  
- **Step 2:** Power BI Data Transformation  
- **Step 3:** Power BI Measures  
- **Step 4:** Data Visualization  
- **Step 5:** Churn Prediction Using Random Forest  
- **Step 6:** Visualization of Predicted Data  

---

## **3. Key Findings and Recommendations**  

📌 **Primary Reasons for Churn:** Competitors offering better devices and deals, followed by poor customer support, pricing issues, and flexible contracts.  

### **Demographics Analysis**  
- **Women over 50** have a high churn rate due to competitors’ superior devices.  
  - **Recommendation:** Improve device offerings and provide upgrade incentives.  
- **Men with a tenure of 18-24 months in Chhattisgarh** experience 100% churn due to pricing and service dissatisfaction.  
  - **Recommendation:** Adjust regional pricing and enhance customer support.  

### **Account Information Analysis**  
- **Mailed Check (37.8%) and Bank Withdrawal (34.4%)** have the highest churn rates.  
  - **Recommendation:** Encourage Credit Card payments with cashback/discount incentives.  
- **Month-to-month contracts have an almost 50% churn rate.**  
  - **Recommendation:** Offer discounts for long-term contracts to boost commitment.  

### **Service Usage Analysis**  
- **Fiber Optic internet has the highest churn rate (41.1%)**, likely due to service issues or cost.  
  - **Recommendation:** Enhance service quality and introduce flexible pricing plans.  
- **Customers not using value-added services** like Device Protection, Online Backup, and Security churn at higher rates.  
  - **Recommendation:** Promote bundled service packages at competitive prices.  
- **Churn remains high even among customers subscribed to Internet, Phone, and Unlimited Data.**  
  - **Recommendation:** Investigate service quality issues and conduct customer surveys.  

### **Churn Prediction for New Customers**  
- **92% of new customers (380/411) are at high risk of churning.**  
  - **Recommendation:** Implement early engagement strategies and personalized retention offers.  

---

## **4. Limitations and Areas for Improvement**  
- The dataset may not capture long-term trends; multi-year analysis is needed.  
- Lack of direct customer feedback makes it difficult to assess real user experience.  

---

## **5. Repository Structure**  
- 📂 Customer_Data.csv → Raw datasets
- 📂 churn_script.sql → SQL scripts for ETL and data analysis
- 📂 ChurnAnalysis.pbix → Power BI file
- 📂 ChurnAnalysis.pdf → Images of Power BI reports
- 📂 Churn Prediction/ → Jupyter Notebook for churn prediction
- 📜 README.md → Project documentation (this file)
