# Experiment 4: Generate Association Rules using Apriori Algorithm in Orange

* **Student Name:** Divyanshu Chandra[cite: 1]
* **Registration Number:** RA2411027020177[cite: 1]
* **Course:** Data Warehousing and Data Mining[cite: 1]

---

## 🎯 Aim
To generate association rules from a transaction dataset using the Apriori algorithm in Orange Data Mining[cite: 5].

## 🛠️ Software & Widgets
* **Software:** Orange Data Mining[cite: 5]
* **Widgets:** Datasets, Association Rules[cite: 5]

## 📚 Theory
Association rule mining finds items or attribute values that occur together[cite: 5]. A rule $A \rightarrow B$ is judged by its support (how often A and B occur together), confidence (how often B occurs when A does) and lift (how much more often they occur together than by chance)[cite: 5].

## 📋 Procedure
Load the Titanic dataset (2201 instances) with the Datasets widget and connect it to Association Rules[cite: 5]. Set Min. support to 10% and Min. confidence to 80%, then click Find Rules[cite: 5].

## 📊 Result
11 rules were found[cite: 5]. For example, `status=crew` $\rightarrow$ `age=adult` has support 0.402, confidence 1.000 and lift 1.052, and `status=crew, sex=male` $\rightarrow$ `age=adult` also has confidence 1.000[cite: 5].
