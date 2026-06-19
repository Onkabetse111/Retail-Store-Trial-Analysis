# Retail-Store-Trial-Analysis
End-to-end retail analytics project using Python to evaluate store trial performance. Includes data cleaning, KPI engineering, exploratory data analysis, control store selection, data visualization, and business recommendations for strategic decision-making.

## 📖 Executive Summary
Retail organisations often conduct store trials to evaluate new business initiatives before implementing them across multiple locations. The challenge is determining whether changes in store performance are the result of the trial itself or external factors such as seasonality and market trends.

This project evaluates the effectiveness of a retail store trial conducted in Stores 77, 86, and 88. Using Python, I identified statistically comparable control stores, analysed pre-trial and trial-period performance, and translated the findings into actionable business recommendations.

The project demonstrates how data can be used to support strategic business decisions through evidence-based analysis rather than relying on intuition alone.

## 🎯 Business Problem
A retail company conducted a trial in three stores to determine whether a new strategy could improve sales performance.

Simply observing an increase in sales is not enough to conclude that the trial was successful because other external factors may have influenced all stores during the same period.

To accurately measure the impact of the trial, suitable control stores first had to be identified. These stores serve as a benchmark, allowing the performance of trial stores to be compared against similar stores that did not participate in the trial.

The objective was to answer the following business question:

Did the trial implemented in Stores 77, 86, and 88 improve store performance compared to similar non-trial stores?


## 🎯 Project Objectives

- Prepare and clean transactional retail data.
- Create monthly business performance metrics.
- Identify suitable control stores using statistical analysis.
- Compare trial and control stores before and during the trial.
- Evaluate trial effectiveness.
- Present findings through data visualisations.
- Provide business recommendations for future strategic decisions.


## 📂 Dataset

The dataset contains transaction-level retail information, including:

- Store Number
- Transaction Date
- Customer Identifier
- Product Details
- Quantity Purchased
- Total Sales Revenue

The data was aggregated into monthly store-level metrics to support trend analysis and performance comparisons.


## 📊 Key Performance Indicators (KPIs)

The following business metrics were created:

### KPI 
Total Sales Revenue - Overall store Performance
Number of Customers - Customer Traffic
Total Transactions - Purchase activity
Transactions per Customer - Shopping frequency
Chips per Customer - Basket size
Average Price per Unit - Pricing behaviour

These KPIs provide a comprehensive view of store performance and customer purchasing behaviour.

## 🔍 Methodology

### 1. Data Preparation

The transactional dataset was cleaned and transformed into monthly store-level summaries.

Key preprocessing steps included:

Converting transaction dates into monthly periods.
Aggregating sales and customer metrics.
Creating business KPIs.
Preparing data for time-series comparison.

### 2. Exploratory Data Analysis (EDA)

Exploratory analysis was conducted to understand:

Monthly sales trends
Customer purchasing behaviour
Transaction frequency
Store performance over time

This stage ensured data quality and provided context before selecting control stores.

### 3. Control Store Selection

Selecting an appropriate control store was the most critical stage of the project.

A combination of analytical techniques was used:

**Pearson Correlation Analysis**

Measured the similarity of historical sales trends between stores.

**Sales Magnitude Comparison**

Ensured candidate stores operated at comparable sales volumes.

**Visual Validation**

Sales trends were plotted to confirm that trial and control stores behaved similarly before the trial period.

This combination produced a more reliable control selection than relying on correlation alone.


## 📈 Selected Control Stores

Trial Store vs Selected Control Store
77 vs 233
86 vs 155
88 vs 203

## 💡 Key Findings
**🟢 Store 77**
Consistently outperformed the selected control store.
Demonstrated positive sales uplift across most of the trial period.
Indicates successful implementation of the trial strategy.

**🟡 Store 86**
Experienced strong initial improvement.
Performance became less consistent during later months.
Additional investigation is recommended before expanding the strategy.

**🟢 Store 88**
Delivered the strongest and most sustained improvement.
Consistently exceeded the performance of the control store.
Demonstrated the clearest evidence of trial success.


## 📊 Visualisations

The project includes visualisations illustrating:

Pre-trial control store validation
Monthly sales comparisons
Trial vs. control performance
Sales trend analysis

### Example Visualisations

Pre-Trial Sales Comparison
Trial Performance Comparison
Monthly Sales Trends


## 📌 Business Insights

This analysis demonstrated that:

- Statistical comparison alone is insufficient when selecting control stores.
- Business context is essential when validating analytical findings.
- Combining correlation analysis, sales magnitude comparison, and visual validation improve          decision-making.
- Store 88 exhibited the strongest evidence that the trial positively influenced sales performance.



## ✅ Recommendations

Based on the findings:

- Expand the trial strategy implemented in Store 88 to similar stores.
- Consider rolling out the Store 77 strategy after continued monitoring.
- Investigate Store 86 to determine why performance improvements were not sustained.
- Continue using a combination of statistical analysis and business validation when evaluating       future store trials.





## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Git
- GitHub

## 🚀 Skills Demonstrated

This project highlights practical experience in:

- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis (EDA)
- Feature Engineering
- KPI Development
- Retail Analytics
- Business Analytics
- Statistical Analysis
- Correlation Analysis
- Experimental Design
- Data Visualisation
- Business Storytelling
- Stakeholder Reporting


## ⚙️ Installation

Clone the repository:

git clone https://github.com/Onkabetse111/Retail-Store-Trial-Analysis

Install dependencies:

pip install -r requirements.txt

Launch Jupyter Notebook:

jupyter notebook

Open:

notebooks/Quantium_Store_Trial_Analysis.ipynb

---

### 🔮 Future Improvements

Potential enhancements include:

- Statistical hypothesis testing
- Time-series forecasting
- Interactive Power BI dashboard
- Customer segmentation
- Market basket analysis
- Predictive analytics using machine learning

---

## 👤 About Me

I am an aspiring Data Analyst with a strong interest in transforming data into actionable business insights.

My current areas of focus include:

Data Analytics
Business Intelligence
Python
SQL
Power BI
Machine Learning

I am actively building projects that demonstrate practical analytical skills and support data-driven decision-making.

---

## 📄 License

This project is licensed under the MIT License.

---

### ⭐ If you found this project interesting, feel free to star the repository or connect with me on LinkedIn.












