# Experiment 9: Demonstration of Clustering Process on iris.arff Using Simple K-Means

* **Student Name:** Divyanshu Chandra[cite: 1]
* **Registration Number:** RA2411027020177[cite: 1]
* **Course:** Data Warehousing and Data Mining[cite: 1]

---

## 🎯 Aim
To demonstrate clustering on the iris data using K-Means in Orange Data Mining and to interpret the resulting clusters[cite: 10].

## 🛠️ Software & Widgets
* **Software:** Orange Data Mining[cite: 10]
* **Widgets:** Datasets, k-Means, Select Columns, Tree, Tree Viewer[cite: 10]

## 📚 Theory
Clustering groups similar observations without using class labels[cite: 10]. A decision tree trained on the cluster labels shows which attributes separate the clusters[cite: 10].

## 📋 Procedure
Run k-Means with $K=3$ on Iris[cite: 10]. Connect the output to Select Columns (1), keep the four measurements as features, set Cluster as Target and ignore the original iris class[cite: 10]. Connect it to Tree and then to Tree Viewer[cite: 10].

## 📊 Result
Clustering was demonstrated with $K=3$[cite: 10]. The tree (11 nodes, 6 leaves) first splits on petal length $\le 1.9$, which isolates cluster C2 completely (50 of 50), and then separates C1 and C3 using sepal length, sepal width and petal width[cite: 10].
