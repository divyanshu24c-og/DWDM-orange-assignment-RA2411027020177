# Experiment 3: Data Transformation using Orange

* **Student Name:** Divyanshu Chandra[cite: 1]
* **Registration Number:** RA2411027020177[cite: 1]
* **Course:** Data Warehousing and Data Mining[cite: 1]

---

## 🎯 Aim
To perform data transformation on a dataset using Orange Data Mining by standardizing the numeric attributes of the selected columns[cite: 4].

## 🛠️ Software & Widgets
* **Software:** Orange Data Mining[cite: 4]
* **Widgets:** Datasets, Impute, Select Columns, Preprocess, Data Table[cite: 4]

## 📚 Theory
Data transformation converts data into a form suitable for mining[cite: 4]. Standardization rescales a numeric attribute to mean 0 and variance 1, so that attributes measured on different scales become comparable[cite: 4].

## 📋 Procedure
Connect Select Columns to the Preprocess widget and add the Normalize Features preprocessor with the option "Standardize to $\mu=0, \sigma^2=1$"[cite: 4]. Connect the output to Data Table (2)[cite: 4].

## 📊 Result
The numeric attributes (ST by exercise, major vessels colored) now hold standardized values such as 1.087 and -0.723, while the 303 instances and 7 features are retained[cite: 4].
