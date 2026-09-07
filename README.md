# 📊 Data Analytics Project

# Customer_Shopping_Behavior_Analysis
Data analytics project showcasing customer behavior analysis using python, MySQL and Power BI.

## Overview
This project demonstrates an end-to-end **data analytics workflow**, starting from raw data loading and exploration to SQL analysis, data visualization, dashboard development, and business reporting.

The project uses **Python, MySQL, and Power BI** to transform raw data into meaningful insights and present them in an easy-to-understand format.

### Project Workflow

**Dataset → Python EDA → Data Cleaning → MySQL Analysis → Power BI Dashboard → Report → Presentation**

---

## 📁 Dataset

The project uses a structured dataset containing business-related records for analysis.

The dataset was initially loaded into Python for:

* Understanding the data structure
* Checking data types
* Identifying missing values
* Detecting duplicates
* Identifying outliers
* Understanding distributions and patterns
* Preparing the data for further analysis

---

## 🛠️ Tools & Technologies

| Tool                     | Purpose                                  |
| ------------------------ | ---------------------------------------- |
| **Python**               | Data loading, cleaning, EDA and analysis |
| **Pandas**               | Data manipulation and preprocessing      |
| **NumPy**                | Numerical analysis                       |
| **Matplotlib / Seaborn** | Data visualization                       |
| **MySQL**                | SQL-based data analysis                  |
| **Power BI**             | Interactive dashboard development        |
| **Microsoft PowerPoint** | Project presentation                     |
| **Jupyter Notebook**     | Python-based analysis                    |

---

## 🔍 Project Steps

### 1. Data Loading

The dataset was imported into Python using Pandas.

Key activities included:

* Loading the dataset
* Inspecting rows and columns
* Checking dataset dimensions
* Reviewing column names and data types
* Generating basic statistical summaries

---

### 2. Exploratory Data Analysis (EDA)

EDA was performed to understand the characteristics and patterns within the dataset.

The analysis included:

* Univariate analysis
* Bivariate analysis
* Distribution analysis
* Correlation analysis
* Trend identification
* Category-wise comparisons
* Outlier detection

Visualizations were created to make the findings easier to interpret.

---

### 3. Data Cleaning

The raw dataset was cleaned and prepared for analysis.

Major data-cleaning activities included:

* Handling missing values
* Removing duplicate records
* Correcting data types
* Standardizing categorical values
* Formatting date and numerical columns
* Handling inconsistent or invalid data
* Treating outliers where required

The cleaned dataset was then prepared for SQL analysis and dashboard development.

---

### 4. SQL Analysis using MySQL

The cleaned data was loaded into **MySQL** for structured querying and analysis.

SQL queries were used to answer business-oriented questions such as:

* What are the overall key metrics?
* Which categories or segments perform the best?
* What are the major trends over time?
* Which products/customers/regions contribute the most?
* What are the top and bottom performing segments?
* How do different categories compare?

SQL concepts used include:

* `SELECT`
* `WHERE`
* `GROUP BY`
* `ORDER BY`
* `HAVING`
* Aggregate functions
* `CASE`
* Subqueries
* Joins
* Date-based analysis
* Window functions, where applicable

---

### 5. Power BI Dashboard

The analyzed data was connected to **Power BI** to create an interactive dashboard.

The dashboard includes:

* KPI cards
* Charts and graphs
* Category-wise analysis
* Trend analysis
* Filters and slicers
* Interactive visualizations
* Business performance indicators

The dashboard was designed to provide a quick overview of the most important insights and allow users to explore the data interactively.

---

## 📊 Dashboard

The Power BI dashboard provides an interactive view of the key business metrics and analytical findings.

### Key Dashboard Areas

* **Overall Performance**
* **Trends Over Time**
* **Category / Segment Analysis**
* **Geographical Analysis**, where applicable
* **Top & Bottom Performers**
* **Key Performance Indicators**

> 📌 Add your Power BI dashboard screenshot here.

```markdown
![Power BI Dashboard](images/dashboard.png)
```

---

## 📈 Results & Key Insights

The analysis helped identify important patterns and business insights from the dataset.

Key findings include:

* Identification of major performance trends
* Comparison of different categories and segments
* Identification of high- and low-performing areas
* Understanding of changes over time
* Identification of potential areas for improvement
* Development of data-driven business recommendations

The final dashboard and report convert these findings into a format that can be easily understood by business stakeholders.

---

## 📄 Project Deliverables

The project includes the following deliverables:

```text
├── Dataset
├── Python EDA Notebook
├── Cleaned Dataset
├── MySQL Queries
├── Power BI Dashboard
├── Analytical Report
└── PowerPoint Presentation
```

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
```

### 2. Install Python Dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Run the Python Analysis

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Open the EDA notebook and run the cells sequentially.

### 4. Set Up MySQL

* Install and start MySQL Server.
* Create the required database.
* Import the cleaned dataset.
* Execute the SQL scripts provided in the `sql` folder.

Update the database connection details if required.

### 5. Open the Power BI Dashboard

Open the `.pbix` file using **Microsoft Power BI Desktop**.

If required, update the data source or database connection settings.

---

## 📂 Repository Structure

```text
data-analytics-project/
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── notebooks/
│   └── EDA.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── powerbi/
│   └── dashboard.pbix
│
├── report/
│   └── project_report.pdf
│
├── presentation/
│   └── project_presentation.pptx
│
├── images/
│   └── dashboard.png
│
└── README.md
```

---

## 🎯 Skills Demonstrated

This project demonstrates practical experience in:

* Data Analysis
* Exploratory Data Analysis
* Data Cleaning
* Python
* Pandas & NumPy
* Data Visualization
* SQL & MySQL
* Power BI
* Dashboard Development
* Business Intelligence
* Data Storytelling
* Report Writing
* Presentation Development

---

## 💡 Conclusion

This project demonstrates an end-to-end approach to solving a data analytics problem using **Python, SQL, and Power BI**.

It showcases the ability to work with raw datasets, clean and analyze data, extract insights using SQL, build interactive dashboards, and communicate findings through reports and presentations.

**The project focuses on turning raw data into actionable business insights through a structured and data-driven approach.**
