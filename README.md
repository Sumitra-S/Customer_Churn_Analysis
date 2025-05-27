## 📊 Customer Churn Analysis – EDA Summary
This notebook performs **Exploratory Data Analysis (EDA)** on a telecom customer churn dataset to uncover patterns and insights related to customer retention and churn.

### 🧱 **Notebook Structure**

1. **📥 Data Loading**

   * Imported data using `pandas`
   * Displayed initial rows and dataset structure

2. **🧹 Data Cleaning**

   * Handled missing and blank values in `TotalCharges`
   * Checked for null values and duplicates
   * Mapped binary values (e.g., `SeniorCitizen`) for clarity

3. **📈 Data Visualization**

   * Countplots and pie charts for:

     * Overall churn distribution
     * Churn by gender, senior status, and contract type
     * Service usage vs churn (StreamingTV, InternetService, etc.)
   * Histograms for tenure and monthly charges
   * Boxplots for outlier detection
   * (Suggested) Heatmap for feature correlations

4. **📌 Key Insights (suggested to add)**

   * Customers with month-to-month contracts tend to churn more
   * Higher monthly charges show a higher churn rate
   * Senior citizens churn more frequently than younger customers


