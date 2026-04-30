
To make this compatible with a GitHub `README.md`, I have formatted the report in **Markdown**. You can copy the code block below directly into your GitHub repository. 

Since GitHub requires hosted image links, I have included placeholders for your charts. To display them on GitHub, you should save the graphs from your Python code (which I've helped you generate) as `.png` files, upload them to your repository (e.g., in an `images/` folder), and update the image paths.

### Copy and Paste the following into your `README.md`:

```markdown
# Customer Churn Analysis & Prediction 📊

## 1. Executive Summary
This project analyzes customer attrition for a telecommunications provider to identify key drivers of churn and develop a proactive retention strategy. By leveraging a Logistic Regression model, we segmented customers into four risk tiers. The analysis reveals that targeting the "High Risk" segment with a strategic discount campaign could yield a **341% ROI**, saving approximately **$366,153 in lifetime value (LTV)**.

---

## 2. Business Problem
In the highly competitive Telco industry, the cost of acquiring a new customer is significantly higher than retaining an existing one. Our dataset shows an overall **churn rate of 33.9%**.
* **Objective:** Predict which customers are likely to churn.
* **Goal:** Shift from reactive support to proactive retention using data-driven risk scoring.

---

## 3. Methodology
The project followed a standard data science pipeline:
1. **Data Simulation:** Generated 7,043 records mimicking real-world patterns (tenure, contract types, and charges).
2. **Feature Engineering:** Performed Label Encoding for categorical variables and Standard Scaling for numerical features.
3. **Modeling:** Trained a Logistic Regression model to provide interpretable coefficients for business stakeholders.
4. **Risk Tiering:** Predicted probabilities were converted into four categories: Low, Medium, High, and Critical.

---

## 4. Key Results & Visualizations

### Churn by Contract Type
Contract type is the most significant indicator of churn. Month-to-month customers are nearly 4x more likely to leave than those on two-year plans.

![Churn by Contract Type](images/churn_by_contract.png)
*(Note: Upload your 'project6_customer_churn.png' to an images folder to see this graph)*

### Model Performance (ROC Curve)
The model achieved an **AUC of 0.697**, providing a solid baseline for identifying the probability of churn across the customer base.

![ROC Curve](images/roc_curve.png)

---

## 5. Skills & Tools
* **Languages:** Python (Pandas, NumPy)
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Logistic Regression, Train-Test Split, Scalers)
* **Domain Knowledge:** ROI Calculation, Customer Lifetime Value (LTV) Analysis, Risk Segmentation

---

## 6. Business Impact & Retention ROI
By focusing resources on the **15.7% of customers** identified as "High Risk," we can optimize marketing spend:
* **Targeted Customers:** 1,107
* **Estimated Retention (35% Success):** 387 customers
* **Campaign Cost:** $83,025 (Discount offers)
* **Projected Revenue Saved:** $366,153
* **Net ROI:** **341%**

---

## 7. Next Steps
* **Model Tuning:** Implement Random Forest or XGBoost to capture non-linear relationships and improve AUC.
* **Feature Expansion:** Integrate customer support ticket frequency and payment history for higher precision.
* **Automated Dashboard:** Export results to Power BI for real-time monitoring of churn risk tiers.

---
*Created by Andre Townsend, MBA | Data Analytics Portfolio Project*
```

### Instructions for the Images:
1.  **Run your Python code** to generate the `project6_customer_churn.png` file.
2.  **Upload the image** to your GitHub repository (usually in a folder named `images`).
3.  **Update the link** in the Markdown code (e.g., `![Churn Chart](images/your_image_name.png)`) to point to your specific file path.
