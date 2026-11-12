# 📊 Sales & Revenue Analytics Dashboard

An interactive business intelligence dashboard built using **Python, Pandas, Plotly, and Streamlit** to analyze sales performance, monitor revenue, and generate meaningful business insights.

This project allows users to upload sales data from CSV and Excel files or connect to a SQL database, explore key business metrics, identify top-performing products, and understand revenue trends through interactive visualizations.

Designed as an academic and portfolio project, it demonstrates practical skills in data analytics, data visualization, business intelligence, and Python application development.

---

## 🎯 Project Objectives

The main objective of this project is to transform raw sales data into meaningful business information.

The dashboard helps users:

- Monitor overall sales and revenue performance.
- Analyze monthly, quarterly, and yearly revenue trends.
- Identify profitable products and categories.
- Compare sales performance across different regions.
- Understand customer purchasing patterns.
- Discover business opportunities through automated insights.

## ✨ Key Features

### 1. Multiple Data Sources
- Upload CSV files.
- Import Excel files (.xlsx).
- Load data from SQLite databases.
- Extendable database support using SQLAlchemy.

### 2. Business KPI Overview

The dashboard displays important business performance indicators:

| KPI | Description |
|---|---|
| Total Revenue | Overall revenue generated |
| Total Sales | Total units sold |
| Total Orders | Number of unique orders |
| Average Order Value | Average revenue per order |
| Total Profit | Total profit generated |
| Profit Margin | Percentage of revenue converted into profit |
| Revenue Growth | Change in revenue over time |

### 3. Interactive Data Visualizations

- Monthly and yearly revenue trends.
- Sales performance over time.
- Top 10 performing products.
- Category-wise revenue distribution.
- Region-wise sales comparison.
- Profitability analysis.
- Customer segment analysis.
- Product revenue contribution.

### 4. Interactive Filters

Users can explore data using:

- Date range selection.
- Product category filters.
- Region filters.
- Customer segment filters.
- Order status filters.
- Product name search.

All charts and KPIs update according to the selected filters.

### 5. Business Insights

An automated insights section provides useful observations, including:

- Highest revenue-generating products.
- Best-performing sales regions.
- Monthly revenue growth or decline.
- Most profitable product categories.
- Overall business performance.

### 6. Data Export

- Download filtered sales data in CSV format.
- Analyze exported data using Excel or other analytics tools.

### 7. Data Validation

- Checks required columns.
- Handles missing values.
- Converts numeric and date columns.
- Displays understandable error messages.
- Handles empty datasets and filter results.

---

## 🛠 Technology Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data processing and analysis |
| NumPy | Numerical operations |
| Plotly | Interactive charts |
| Streamlit | Dashboard development |
| SQLite | Database management |
| SQLAlchemy | Database connectivity |
| OpenPyXL | Excel file processing |

---

## 📁 Project Structure

```text
sales-revenue-dashboard/
│
├── app.py
│
├── src/
│   ├── __init__.py
│   ├── data_loader.py
│   ├── kpi_calculator.py
│   ├── visualizations.py
│   └── database.py
│
├── utils/
│   └── data_generator.py
│
├── data/
│   ├── sample_sales_data.csv
│   ├── sample_sales_data.xlsx
│   └── sales_database.db
│
├── assets/
│   └── screenshots/
│
├── .streamlit/
│   └── config.toml
│
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md
```

---

## ⚙️ Installation and Setup

### Prerequisites

Make sure the following are installed:

- Python 3.10 or higher
- Git
- Visual Studio Code (recommended)
- pip package manager

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/sales-revenue-dashboard.git
```

### Step 2: Open Project Directory

```bash
cd sales-revenue-dashboard
```

### Step 3: Create Virtual Environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### Step 4: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 5: Run the Dashboard

```bash
streamlit run app.py
```

Open the following address in your browser:

```text
http://localhost:8501
```

The dashboard will start locally and display the available sales analytics.

---

## 📂 Dataset Information

The project includes a synthetic sales dataset for demonstration and testing.

The sample dataset can contain:

- Multiple years of sales records.
- Different product categories.
- Multiple sales regions.
- Various customer segments.
- Different order statuses.
- Product pricing and profit information.

### Expected Dataset Columns

| Column | Description |
|---|---|
| OrderID | Unique order identifier |
| OrderDate | Date of purchase |
| CustomerSegment | Customer category |
| Region | Sales region |
| ProductCategory | Product category |
| ProductName | Product name |
| Quantity | Number of units sold |
| UnitPrice | Price per unit |
| NetRevenue | Revenue after discounts |
| Profit | Profit generated |
| OrderStatus | Current order status |

Users can upload their own datasets after matching the required column structure.

---

## 📈 Business Intelligence & Insights

This dashboard is designed to help users move beyond basic data visualization and understand actual business performance.

Example business questions it can answer:

1. Which product generates the highest revenue?
2. Which region contributes the most to overall sales?
3. How does revenue change month by month?
4. Which category provides the highest profit margin?
5. Are sales increasing or decreasing?
6. Which customer segment generates the most revenue?

These insights can help businesses improve pricing strategies, inventory planning, product selection, and sales performance.

---

## 🚀 Future Enhancements

The following features can be added in future versions:

- AI-powered sales forecasting.
- Machine learning-based revenue prediction.
- Customer segmentation using clustering.
- Customer Lifetime Value (CLV) analysis.
- Advanced geographical sales maps.
- PDF and Excel report generation.
- User authentication and role-based access.
- MySQL and PostgreSQL integration.
- Sales anomaly detection.
- Docker-based deployment.
- Automated testing using PyTest.

---

## 🎓 Learning Outcomes

Through this project, the following technical concepts are demonstrated:

- Data cleaning and preprocessing.
- Exploratory Data Analysis (EDA).
- KPI calculation and performance tracking.
- Interactive data visualization.
- Database connectivity.
- Python application development.
- Business intelligence and analytical thinking.
- Generating actionable business insights.

---

## 👨‍💻 Author

**Arpit Patidar**

B.Tech – Internet of Things (IoT)

Interested in Python Development, Data Analytics, Artificial Intelligence, and Software Development.

---

## 📜 License

This project is intended for educational and portfolio purposes.

Released under the MIT License.

---

⭐ If you find this project useful, consider giving it a star on GitHub!

**Built with Python, Data Analytics & Business Intelligence.**
