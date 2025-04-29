# ⚙️ Distributed Database Management & Channel Recommendation Projects

<p align='center'>
  <a href="https://github.com/yuvalmar16">Yuval Margolin</a> | 
  <a href="https://github.com/RavidGersh59">Ravid Gersh</a>
</p>

---

## 🧠 Overview

This repository includes two projects developed as part of a distributed database and data analysis course.  
The focus is on applying big data principles using PySpark, Spark SQL, clustering techniques, and notebook-based workflows for solving real-world media and broadcasting challenges.

---

## 📁 Files

| File | Description |
|------|-------------|
| `project1_part1.ipynb` | Implements spam detection, DMA popularity analysis, and wealth-based recommendations using PySpark and Spark SQL. |
| `project1_part2.ipynb` | Continuation of Project 1, focused on deeper data processing, optimization, and evaluation. |
| `Project_2.ipynb` | Complete notebook for dynamic channel recommendation using demographic clustering and real-time viewing data. |

---

## 📌 Project 1: Distributed Database Management – Media Association

### 🎯 Objective  
Assist the **Distributed Media Association (DMA)** in organizing and analyzing large-scale broadcasting data to support decisions on content delivery and customer insights.

### 🧩 Key Tasks

- **Spam Detection**  
  Identify and filter out malicious or irrelevant records from the *Daily Program Data* using PySpark and conditional logic.

- **Data Structuring & Access**  
  Design a data schema for fast and efficient access by DMA clients.

- **Popularity Analysis by Region**  
  Analyze and rank the popularity of genres across different DMAs using aggregated viewing data.

- **Wealth-Based Content Optimization**  
  Prioritize content delivery to DMAs based on wealth scores and genre exclusivity, optimizing for strategic business value.

### 🛠 Skills Used

- Data Cleaning & Preprocessing (PySpark)
- Spark SQL & conditional filtering
- Wealth score computation and content targeting
- Data schema design and deployment across DMAs

---

## 📌 Project 2: Personalized Channel Recommendation for Lukewarm™ Cable

### 🎯 Objective  
Help **Lukewarm™ Cable** recommend personalized channel bundles to new clients by analyzing viewing patterns, demographics, and real-time streaming data.

### 🧩 Key Tasks

- **Static Demographic Analysis**  
  Extract features from household demographic data and prepare it for modeling.

- **PCA & K-Means Clustering**  
  Apply Principal Component Analysis for dimensionality reduction and K-Means to identify household clusters.

- **Subset Segmentation**  
  Further divide clusters into subsets for targeted analysis.

- **Viewing Pattern Analysis**  
  Identify unique content preferences and habits within each cluster to inform channel recommendations.

- **Streaming Analysis (Real-Time)**  
  Use **Spark Streaming** to perform ongoing analysis of live viewing data.

- **Batch Processing Comparison**  
  Perform batch-wise comparisons to detect evolving trends in different clusters.

### 🛠 Skills Used

- Feature Engineering & Demographic Modeling
- PCA and K-Means Clustering
- PySpark (Batch + Streaming)
- Visualization and Cluster Interpretation
- Dynamic recommendation logic

---

## 💡 Technologies & Tools

- Python 3.x  
- Jupyter Notebooks  
- Apache Spark & PySpark  
- Spark SQL  
- Spark Streaming  
- Scikit-learn (PCA, clustering)  
- Pandas, NumPy, Matplotlib, Seaborn

---

## 📎 How to Run

1. Clone the repository
2. Make sure Spark and Jupyter are installed and configured
3. Launch the notebooks one by one:
   ```bash
   jupyter notebook project1_part1.ipynb
   jupyter notebook project1_part2.ipynb
   jupyter notebook Project_2.ipynb
   ```

---

## 🤝 Contributors

- [Yuval Margolin](https://github.com/yuvalmar16)
- [Ravid Gersh](https://github.com/RavidGersh59)

---

