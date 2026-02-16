**Customer Behavior Analysis
 Overview**

This project is an end-to-end data analytics workflow that uncovers meaningful insights from customer transaction data using Python, SQL, and Power BI. The analysis includes loading and cleaning data, performing Exploratory Data Analysis (EDA), executing analytical queries in a SQL database (e.g., PostgreSQL, MySQL, or SQL Server), building a dynamic Power BI dashboard, and producing a report and presentation with Gamma. The goal is to support data-driven decisions for business stakeholders.

📁 **Dataset**

The dataset used for this project is customer_shopping_behavior(csv).csv, which contains transaction and demographic data for customer purchases.

Key contents include:

Customer identifiers

Transaction dates and amounts

Product purchase details

Demographic attributes


**Tools & Technologies**
| Task                        | Tool                                          |
| --------------------------- | --------------------------------------------- |
| Data loading & cleaning     | Python (pandas, numpy)                        |
| Exploratory Data Analysis   | Python (matplotlib, seaborn)                  |
| Database storage & querying | PostgreSQL / MySQL / SQL Server (SQL scripts) |
| Dashboard creation          | Power BI                                      |
| Report writing              | Markdown / PDF                                |
| Presentation                | Gamma                                         |

## Project Steps

### 1. Data Loading (Python)
- Loaded dataset using pandas
- Checked shape and data types
- Identified missing values

### 2. Exploratory Data Analysis (EDA)
- Generated summary statistics
- Analyzed customer demographics
- Identified top-selling categories
- Analyzed revenue trends
- Created visualizations (bar charts, line charts, histograms)

### 3. Data Cleaning
- Handled missing values
- Converted date column to datetime format
- Removed duplicates
- Standardized categorical values
- Created calculated columns if required

### 4. SQL Analysis
- Imported cleaned dataset into SQL database
- Created tables
- Executed analytical queries:
  - Total revenue by category
  - Revenue by gender
  - Monthly sales trend
  - Top customers by spending
  - Average purchase value
- Used GROUP BY, ORDER BY, JOIN, aggregate functions

### 5. Power BI Dashboard
- Created KPI cards
- Built sales trend charts
- Built category-wise revenue charts
- Added interactive filters
## Key Insights
- Identified top-performing product categories
- Found highest revenue customer segments
- Detected monthly sales patterns
- Calculated average customer spending

## How to Run

1. Clone the repository
   git clone https://github.com/arya1607/Customer-Behavior-Analysis.git

2. Install libraries
   pip install pandas numpy matplotlib seaborn

3. Run Jupyter Notebook

4. Import data into SQL and run queries

5. Open Power BI dashboard and refresh data
