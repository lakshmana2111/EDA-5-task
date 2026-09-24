# 🏥 Healthcare Data Analysis

## 📌 Project Overview

This project analyzes a healthcare dataset using **Python and Pandas**. The notebook performs basic data loading, inspection, data cleaning, date conversion, descriptive statistics, and exploratory analysis of patient and billing information.

---

## 📂 Dataset

The project uses the file:

```text
healthcare_raw.csv
```

The dataset contains **500 rows and 9 columns**.

### Columns

| Column              | Description                                             |
| ------------------- | ------------------------------------------------------- |
| `Patient_ID`        | Unique patient identifier                               |
| `Gender`            | Patient gender                                          |
| `Age`               | Patient age                                             |
| `Medical_Condition` | Recorded medical condition                              |
| `Admission_Date`    | Patient admission date                                  |
| `Admission_Type`    | Type of admission such as Routine, Urgent, or Emergency |
| `Medical_Code`      | Medical/ICD10 code                                      |
| `Billing_Amount`    | Patient billing amount                                  |
| `Discharge_Date`    | Patient discharge date                                  |

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab / Jupyter Notebook

---

# 🔄 Project Workflow

## 1. Import Libraries

The project uses **NumPy, Pandas, Matplotlib, and Seaborn** for data processing, analysis, and visualization.

---

## 2. Load the Dataset

The healthcare CSV file is loaded into a Pandas DataFrame.

```python
df = pd.read_csv(_
```
