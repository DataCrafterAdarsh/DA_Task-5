# Task 5 – Python Data Cleaning (House Prices Dataset)

## 📌 Objective
To perform basic data cleaning using Python (Pandas) and understand how Python can replace manual Excel cleaning for large datasets.

---

## 🛠 Tools Used
- JupyterLab
- Python
- Libraries:
  - pandas
  - numpy

---

## 📁 Dataset
House Prices Dataset

---

## 🔍 Steps Performed

1. Imported required libraries (pandas, numpy).
2. Loaded dataset using pd.read_csv().
3. Checked dataset structure using head() and info().
4. Identified missing values using isnull().sum().
5. Filled missing numeric values using median.
6. Filled missing categorical values using mode.
7. Checked and removed duplicate rows.
8. Verified no duplicates were present.
9. Converted data types where required.
10. Created a new column **Price_Category** using qcut().
11. Verified new column using value_counts().
12. Saved final cleaned dataset as CSV file.

---

## 📤 Output Files
- Task5_Cleaning.ipynb  
- cleaned_house_prices.csv  

---

## 📊 New Feature Added
**Price_Category Column**
- Very Low
- Low
- Medium
- High
- Very High

This column categorizes house prices for better analysis.

---

## 💡 Learning Outcome
- Learned how to clean datasets using Pandas.
- Understood handling missing values.
- Learned duplicate removal.
- Created new columns using logic.
- Exported cleaned dataset.
- Understood why Python is better than Excel for big data.

---

## 🚀 Conclusion
This task helped me gain hands-on experience in data cleaning using Python and improved my understanding of real-world data preprocessing.

---

## 👨‍💻 Author
Adarsh Mishra
