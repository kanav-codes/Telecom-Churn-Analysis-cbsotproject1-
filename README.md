# 🚀 Telecom Customer Churn: End-to-End Predictive Analytics & Strategy

## 📌 Overview
This project delivers a comprehensive, end-to-end data science solution to predict customer churn in the telecommunications industry. By leveraging machine learning and customer segmentation, the project transforms raw data into actionable business strategies.

## 🛠 Project Workflow (ATS Optimized)
The project follows a rigorous end-to-end pipeline:
* **Data Cleaning**: Handled missing values (e.g., 'Total Charges') and performed robust preprocessing.
* **Encoding & EDA**: Conducted Exploratory Data Analysis (EDA) and utilized label encoding to prepare data for modeling.
* **Feature Selection**: Optimized the model by identifying the most influential predictors of churn.
* **Machine Learning**: 
    * Implemented **Random Forest Classifier** with `class_weight='balanced'` to handle class imbalance.
    * Performed extensive **Hyperparameter Tuning** to maximize model recall and precision.
* **Advanced Analytics**:
    * **Cross-Validation**: Ensured model robustness through 5-fold cross-validation.
    * **ROC-AUC Analysis**: Evaluated model discriminative power beyond simple accuracy.
    * **Customer Segmentation**: Used **K-Means Clustering** with the Elbow Method to determine optimal 'K' and group customers into strategic personas.

## 💡 Unique Business Insights
* **Financial Impact Quantification**: Calculated the potential monthly revenue loss based on churn predictions, enabling prioritized interventions.
* **Strategic Retention Framework**: 
    * **Loyal Premium**: Exclusive rewards and early access.
    * **Budget Loyal**: Personalized upgrade offers.
    * **High Risk**: Immediate "Save Team" intervention.
* **Explainable AI**: Visualized the **Top 10 Drivers of Churn** to provide business-ready transparency.

## 💡 The "Extra Mile": Value-Added Business Integration
Beyond the standard predictive modeling, I implemented three key analytical enhancements to bridge the gap between Data Science and actual business operations:

1. **Financial Risk Quantification:** I didn't just predict churn; I calculated the **Potential Monthly Revenue Loss**. This allows the business to see the "cost of inaction" and prioritize high-value customers for retention.
2. **Actionable Retention Framework:** Using the model outputs, I mapped customers into specific segments (Loyal Premium, Budget Loyal, High Risk) and defined a **Custom Retention Strategy Map**. This transforms abstract model probabilities into a concrete "Save Team" action plan.
3. **Business-Focused Explainability:** I pivoted from "Black Box" modeling to focus on **Top 10 Churn Drivers**. By identifying critical features like *Contract Type* and *Tenure*, I provided stakeholders with clear, understandable reasons why customers are leaving.

## 📊 Visualizations
![Top 10 Churn Drivers](images/drivers.png)
![Elbow Method](images/elbow.png)
![Cluster Visualization](images/download.png)

## 🛠 Tech Stack
* **Language**: Python
* **Libraries**: Pandas, NumPy, Seaborn, Matplotlib, Scikit-Learn
* **Models**: RandomForestClassifier, KMeans

---
*Created by Kanav Bansal *
