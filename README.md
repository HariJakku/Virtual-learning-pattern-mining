# 📊 Unlocking Patterns in Virtual Learning: A Data Mining Approach

This project analyzes student behavior, satisfaction, and platform usage in virtual learning using **Data Mining**, **Machine Learning**, and **OLAP** methodologies. It leverages a structured survey dataset, applies classification models, and performs multidimensional analysis using MDX queries on OLAP cubes.

---

## 📁 Project Structure

```text
Data-Mining-Virtual-Learning/
│
├── Dataset/                         # Student survey data
│   └── student_survey.csv
│
├── Preprocessing/                  # Orange tool workflows
│   └── orange_workflow.ows
│
├── OLAP_MDX/                       # OLAP analysis using MDX
│   ├── star_schema_queries.mdx
│   ├── snowflake_schema_queries.mdx
│   ├── fact_constellation_queries.mdx
│   └── query_outputs_screenshots
│
├── Report/                         # Final project report
│   └── DM_B9.pdf
│
├── requirements.txt                # Python libraries used
└── README.md                       # You are here

```

## 🎯 Project Objectives

- Analyze student engagement and learning behavior in online platforms.
- Classify students based on satisfaction, challenges, and preferences.
- Perform multidimensional OLAP analysis using Star, Snowflake, and Fact Constellation schemas.
- Evaluate classification models for predicting learner engagement and platform effectiveness.

---

## 📊 Dataset Overview

Collected via a structured Google Form, the dataset includes:

- Age group, education level
- Preferred learning platform (Coursera, Udemy, YouTube, etc.)
- Course type (technical, non-technical)
- Time spent, learning style
- Satisfaction level, challenges faced
- Feature expectations, free vs paid preference

---

## 🔍 Technologies & Tools Used

### 🔢 Machine Learning (Orange Tool)
- Models: Naive Bayes, Random Forest, KNN, SVM, Neural Network
- Metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrix
- Data balancing: SMOTE
- Feature scaling: Min-Max Normalization

### 🧮 OLAP & MDX
- OLAP Schemas: Star, Snowflake, Fact Constellation
- Tools: SQL Server Management Studio (SSMS), SSAS, Visual Studio
- MDX Operations: ROLLUP, SLICE, DICE, DRILL-DOWN, PIVOT

### 📈 Visualization
- Charts, heatmaps, scatter plots, and bar graphs using Orange & OLAP dashboards

---

## 🏆 Key Results

- **Naive Bayes** performed best on real-world data with the highest classification accuracy.
- **Random Forest** excelled on symbolic data (MONK's dataset).
- Time spent and interactive features were key indicators of student satisfaction.
- Most students preferred self-paced, video-based learning modes.

---

## 📌 OLAP MDX Queries

Located in the `/OLAP_MDX/` folder:
- `star_schema_queries.mdx`
- `snowflake_schema_queries.mdx`
- `fact_constellation_queries.mdx`

Query results are visualized and stored as screenshots in the `query_outputs_screenshots/` folder.

---

## 📄 Report

Full project documentation is available in the [`/Report/DM_B9.pdf`](./Report/DM_B9.pdf) file.

---

## 🛠️ How to Run

**1️⃣ Clone the Repository**
```bash
git clone https://github.com/your-username/Data-Mining-Virtual-Learning.git
```

**2️⃣ Navigate into the project directory:**
   ```bash
   cd Data-Mining-Virtual-Learning

   ```
**3️⃣ Install required Python packages:**
   ```bash
   pip install -r requirements.txt


   ```


## 🧑‍🏫 Guided By

**Dr. N. Rajeswari**, Professor & Mentor, Department of Computer Science and Engineering  
*Seshadri Rao Gudlavalleru Engineering College*

## 📝 License

This project is intended solely for **academic and educational purposes**.  
All rights reserved by the respective contributors and guide.





