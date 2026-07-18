# 🔍 SEO Performance & Machine Learning Analysis

> An end-to-end SEO analytics project that combines technical SEO auditing, Machine Learning, and Power BI to measure website optimization performance and generate actionable business insights.

---

## 📖 About the Project

Modern websites generate thousands of technical SEO metrics, making it difficult to evaluate overall website health manually. This project transforms raw SEO crawl data into a quantitative **SEO Health Score** using Machine Learning techniques and presents the results through an interactive Power BI dashboard.

The analysis compares website performance **before and after SEO optimization**, allowing stakeholders to understand the effectiveness of optimization efforts through meaningful KPIs and visual reports.

**Website Analyzed:** wooferzz.com

---

# 🎯 Project Goals

- Build an SEO performance evaluation pipeline.
- Convert raw crawl data into a structured ML-ready dataset.
- Engineer SEO Health Score using technical SEO metrics.
- Predict SEO performance using Machine Learning models.
- Compare website performance before and after optimization.
- Visualize optimization results through an interactive Power BI dashboard.

---

# ⚙️ Project Workflow

```
Screaming Frog Crawl
          │
          ▼
Excel Data Cleaning
          │
          ▼
Python Data Analysis
          │
          ▼
Feature Engineering
          │
          ▼
Machine Learning Models
          │
          ▼
SEO Health Score
          │
          ▼
Power BI Dashboard
          │
          ▼
Business Insights
```

---

# 📂 Dataset Information

The project uses SEO crawl reports generated using **Screaming Frog SEO Spider**.

### Dataset Highlights

- 150 Crawled URLs
- Before & After SEO Optimization Comparison
- Technical SEO Metrics
- Website Performance Metrics
- Core Web Vitals
- Crawl Information

---

# 🧹 Data Preparation

The raw crawl export was transformed into an ML-ready dataset using Microsoft Excel before being analyzed in Python.

### Data Preparation Tasks

- Removed redundant columns
- Converted categorical values into numeric format
- Standardized column names
- Converted text-based metrics into numerical values
- Eliminated unnecessary attributes
- Exported cleaned CSV for Machine Learning

This preprocessing ensured that the dataset required minimal additional cleaning during Python-based analysis. :contentReference[oaicite:1]{index=1}

---

# 📊 Exploratory Data Analysis

Python was used to understand website performance before building predictive models.

The analysis included:

- Dataset Overview
- Before vs After Comparison
- SEO Issue Analysis
- Correlation Analysis
- Feature Engineering
- Performance Improvement Distribution
- Top Improved Pages
- Website Performance Visualization

---

# 🤖 Machine Learning Implementation

Multiple Machine Learning approaches were implemented to answer different business questions.

### Binary Classification

Predicts whether a webpage is likely to improve after SEO optimization.

### Multi-Class Classification

Categorizes webpages into:

- High Improvement
- Low Improvement
- No Improvement

### Regression Model

Predicts the expected improvement value for each webpage.

The project evaluates these models using Accuracy, Precision, Recall, F1-Score, MAE, and R² to compare predictive performance. :contentReference[oaicite:2]{index=2}

---

# 📈 Dashboard Highlights

The Power BI dashboard provides an interactive view of SEO performance using dynamic filters and KPIs.

### Key Performance Indicators

- Total Pages Crawled
- Improved Pages
- Improvement Rate
- Average Performance Score
- Average SEO Health Score
- Average Response Time

### Interactive Visualizations

- Performance Score Comparison
- SEO Health Overview
- Goal Achievement Analysis
- Improvement Distribution
- URL Performance Ranking
- Detailed Page-Level Analysis
- Dynamic Filters and Slicers

The dashboard enables users to explore optimization outcomes at both summary and page levels. :contentReference[oaicite:3]{index=3}

---

# 💡 Key Findings

- Majority of webpages demonstrated measurable improvement after optimization.
- Website performance scores increased significantly after SEO implementation.
- Faster response times were associated with improved SEO scores.
- Content depth emerged as one of the strongest indicators of successful optimization.
- Technical SEO improvements positively influenced overall website health.

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Microsoft Excel
- Power BI
- DAX
- Power Query
- Screaming Frog SEO Spider

---

# 📁 Repository Structure

```
SEO-Performance-ML-Analysis/
│
├── Dataset/
│
├── Notebook/
│
├── Dashboard/
│
├── Documentation/
│
├── Screenshots/
│
├── README.md
│
└── requirements.txt
```

---

# 📸 Dashboard Preview

## SEO Performance Dashboard

> Add your Power BI dashboard screenshot here.

```
Screenshots/dashboard.png
```

---

# 📈 Business Value

This project helps organizations:

- Monitor SEO performance efficiently
- Measure optimization success objectively
- Identify high-impact technical improvements
- Prioritize optimization opportunities
- Support data-driven SEO strategies

---

# 🚀 Future Enhancements

- Real-time SEO monitoring
- Live Google Search Console integration
- Google Analytics integration
- Automated SEO reporting
- Predictive SEO recommendations
- Cloud deployment using Azure
- Streamlit-based web application
- Deep Learning models for SEO prediction

---

# 🎓 Learning Outcomes

Through this project I gained practical experience in:

- Technical SEO analysis
- Data preprocessing
- Feature engineering
- Machine Learning model development
- Model evaluation
- Data visualization
- Power BI dashboard development
- DAX calculations
- Business intelligence reporting

---

# 👩‍💻 Author

**Shruti Chinchalkar**

MCA (Artificial Intelligence & Machine Learning)

### Skills

- Machine Learning
- Data Analysis
- Power BI
- Python
- SEO Analytics
- Business Intelligence

---

# ⭐ Support

If you found this project interesting, consider giving this repository a ⭐ on GitHub.

Your support motivates me to build more Machine Learning and Data Analytics projects.