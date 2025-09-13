# credit-card-data-cleaning
Credit card data has been cleaned using Excel and Power query.

# Credit Card Status Data Cleaning (Excel + Power Query, Kaggle Dataset)

## 📌 Problem Statement
The raw dataset (1,000+ rows) downloaded from Kaggle was unclean and unorganized:
- Column headers were inconsistent and unclear.
- Values were not standardized, with ranges like `<0`, `0<=X<200`, `>=200`.
- Unnecessary or irrelevant columns were present.
- This made performing calculations, generating insights, and creating dashboards difficult.

## ❓ Why Cleaning Was Required
If the data is not properly organized and validated, any calculations, reports, or dashboards built on it may be inaccurate.  
Clean and structured data is critical for reliable analytics and business decision-making.  

---

## 🔧 Data Cleaning Steps
1. **Standardized Columns**  
   - Renamed headers for clarity using Power Query:  
     ```m
     = Table.TransformColumnNames(#"Changed Type", Text.Proper)
     ```
   - Ensured consistent naming convention.  

2. **Converted Range Values to Numeric**  
   - Used Custom & Conditional Columns to replace ranges (`<0`, `0<=X<200`, `>=200`) with numeric values.  
   - Applied similar transformations for *Checking Status, Employment Years, Savings Status*.  

3. **Removed Unnecessary Columns**  
   - Deleted irrelevant columns to make the dataset focused and manageable.  

4. **Validated Data**  
   - Checked for missing or inconsistent values.  
   - Ensured numeric fields were correctly formatted for calculations.  

---

## 📊 Impact of Data Cleaning
- ✅ **Simplified Analysis** – Enabled error-free calculated columns & measures.  
- ✅ **Enhanced Dashboard Quality** – Cleaned data supports meaningful KPIs & visuals.  
- ✅ **Accurate Insights** – Reliable analytics for better business decisions.  
- ✅ **Time Efficiency** – Reduced repetitive corrections, saving analyst time.  
- ✅ **Professional & Trustworthy** – Stakeholders can rely on the dataset for insights.  

---



