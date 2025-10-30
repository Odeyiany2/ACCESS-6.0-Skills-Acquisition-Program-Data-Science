# 📘 Week 2 - Data Manipulation with Pandas

Welcome to **Week 2** of the ACCESS 6.0 Data Science Track!  
This week, we’ll begin working with real-world data using **Pandas**, one of the most powerful libraries for data analysis in Python.  

By the end of this week, you’ll learn how to:
- Load, inspect, and explore datasets in different formats (CSV, Excel, JSON)
- Clean and prepare data for analysis
- Perform basic aggregations, grouping, and filtering
- Understand the business context behind data operations in **Accounting and Finance**



## 🗓️ Weekly Overview

### **Session 3 - Introduction to Pandas: DataFrames, Series & Inspection**
**Objectives:**
- Understand what Pandas is and why it’s essential for data analysis.
- Learn how to load data from CSV files.
- Explore and inspect datasets using functions like `.head()`, `.info()`, `.describe()`, and `.shape`.
- Perform basic selection and filtering operations.
- Discuss how these techniques apply in accounting and business (e.g., inspecting ledger data, customer transactions, or expense categories).

**Instructor Dataset:**  
> [BudgetWise Personal Finance Dataset (Kaggle)](https://www.kaggle.com/datasets/mohammedarfathr/budgetwise-personal-finance-dataset)  
Simulates messy real-world financial transactions — perfect for learning to clean and structure data before analysis.

**Assignment Dataset:**  
> [Warehouse and Retail Sales (Montgomery County)](https://www.kaggle.com/datasets/samanfatima7/warehouse-and-retail-sales-montgomery-county)  (*Tentative*)
Students will use this dataset for independent exercises and assignments.

**Assignment (Due Next Session):**
> Load your assigned dataset in Google Colab and perform the following:
> 1. Display the first and last 5 rows of the data.
> 2. Check the dataset’s shape and column list.
> 3. Identify missing values and data types.
> 4. Print the top 5 customers (or stores) by total sales amount.
> 5. Write one short paragraph (in a markdown cell) explaining a quick insight you discovered.
> 
> **Upload your notebook** to your GitHub repo and paste the link in the shared class sheet.



### **Session 4 - Cleaning & Feature Creation**
**Objectives:**
- Handle missing values and duplicates.
- Parse and standardize dates.
- Create new calculated columns (e.g., `TotalPrice = Quantity * UnitPrice`).
- Perform simple groupby and aggregation operations.
- Save cleaned versions of the dataset to your repo for reuse.

**Instructor Dataset:**  
> [BudgetWise Personal Finance Dataset (Kaggle)](https://www.kaggle.com/datasets/mohammedarfathr/budgetwise-personal-finance-dataset)

**Assignment Dataset:**  
> [Warehouse and Retail Sales (Montgomery County)](https://www.kaggle.com/datasets/samanfatima7/warehouse-and-retail-sales-montgomery-county) (*Tentative*)

**Assignment (Due Next Session):**
> - Remove rows with missing or null values in key columns (e.g., Product or Quantity).  
> - Create a new column for `TotalPrice = Quantity * UnitPrice`.  
> - Create a `Month` column extracted from the `Date` column.  
> - Group by `Month` and compute total revenue per month.  
> - Save the cleaned file as `cleaned_sales.csv` and upload it to your repo.



## 📂 Folder Structure

📁 Week_2/

│

├── 📘 Session3_Pandas_Intro.ipynb

├── 📘 Session4_Data_Cleaning_Feature_Engineering.ipynb

├── 🗂️ datasets/

│ ├── budgetwise_personal_finance.csv

│ ├── retail_sales_montgomery.csv

│
├── 🧩 assignments/

│ ├── Session3_Assignment.ipynb

│ ├── Session4_Assignment.ipynb

│

└── README.md ← (you are here)




## 🧠 Key Takeaways
- **Data inspection** is like reconciling your accounting books — before analysis, always verify the integrity of your data.
- **Feature creation** is similar to deriving financial ratios — new columns help uncover insights.
- **Data cleaning** ensures decisions are based on truth, not noise.



## 📚 Additional Resources
- 📖 [Pandas Documentation](https://pandas.pydata.org/docs/)
- 📘 [10 Minutes to Pandas](https://pandas.pydata.org/pandas-docs/stable/user_guide/10min.html)
- 🎥 [Kaggle Pandas Tutorial Series](https://www.kaggle.com/learn/pandas)
- 🧾 [Data Cleaning in Python: A Practical Guide](https://realpython.com/python-data-cleaning-numpy-pandas/)
- 💡 [Finance Example: Analyzing Sales Transactions using Pandas](https://towardsdatascience.com/analyzing-financial-data-with-pandas-a45e7b3a0ba7)



**✅ Submission Checklist**
- [ ] Notebook pushed to GitHub
- [ ] Cleaned dataset uploaded (if applicable)
- [ ] Short paragraph of insights in markdown cell
- [ ] Link shared in class sheet




**Author:**  
🧑🏽‍🏫 *Miriam Odeyiany (Mimi)*  
Instructor – Data Science Track, ACCESS 6.0 Skills Development Program
Department of Accounting, University of Lagos  


