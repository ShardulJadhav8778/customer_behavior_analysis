# customer_behavior_analysis
Customer Shopping Behavior Analysis Dashboard using Power BI, SQL, and Python to visualize purchasing trends and customer insights

# customer_behavior_analysis

Customer Shopping Behavior Analysis is a data analytics project built to study customer shopping patterns, purchase trends, and business insights.  
This project uses **Python, Pandas, SQL, MySQL, Jupyter Notebook, and Power BI** to clean the data, prepare useful features, store the cleaned data, and build a dashboard-ready dataset.

## Project Files

- `customer_shopping_behavior.csv` — raw dataset
- `Customer_Shopping_Behavior_Analysis.ipynb` — Python notebook for cleaning and analysis
- `customer_behaviour_sql_queries.sql` — SQL queries used for analysis
- `customer_behaviour_dashboard.pbix` — Power BI dashboard file
- `README.md` — project details

## Objective

The main goals of this project are:

- Clean and prepare customer shopping data
- Handle missing values
- Create useful analysis columns
- Store cleaned data in MySQL
- Use the final data for SQL queries and Power BI dashboard
- Find useful business insights from customer shopping behavior

## Dataset Overview

The dataset contains customer shopping details such as:

- Customer age
- Gender
- Item purchased
- Category
- Purchase amount
- Location
- Size
- Color
- Season
- Review rating
- Subscription status
- Shipping type
- Discount applied
- Payment method
- Frequency of purchases

## Tools Used

- Python
- Pandas
- Jupyter Notebook
- SQL
- MySQL
- SQLAlchemy
- PyMySQL
- Power BI

## Project Workflow

1. Load the CSV file into Python
2. Check the data structure
3. Find missing values
4. Fill missing review ratings using the median of each category
5. Clean column names
6. Create an `age_group` column
7. Convert purchase frequency into days
8. Remove unnecessary columns
9. Save the cleaned data into MySQL
10. Use the final data for SQL analysis and dashboard creation

## Key Features

- Data cleaning
- Feature engineering
- Customer segmentation
- Purchase frequency analysis
- MySQL database integration
- Dashboard-ready dataset
- Business insight generation

## How to Run the Project

### 1. Install required packages
```bash
pip install pandas jupyter sqlalchemy pymysql

jupyter notebook

3. Run the notebook

Open Customer_Shopping_Behavior_Analysis.ipynb and run all cells step by step.

MySQL Setup

Before running the notebook, make sure:

MySQL is installed
A database is created
Connection details in the notebook are correct

Update the MySQL connection values in the notebook before running it.

Project Output

After running the project, you will get:

Cleaned customer shopping dataset
New columns like age_group and purchase_frequency_days
Data stored in MySQL
Ready-to-use data for SQL queries
Power BI dashboard-ready dataset

Folder Structure

customer_behavior_analysis/
│
├── customer_shopping_behavior.csv
├── Customer_Shopping_Behavior_Analysis.ipynb
├── customer_behaviour_sql_queries.sql
├── customer_behaviour_dashboard.pbix
└── README.md



Future Scope


Add more visual insights


Build an interactive Power BI dashboard


Perform customer segmentation


Predict customer buying behavior


Compare sales across categories and seasons


Improve business decisions using advanced analytics


Conclusion
This project helps understand customer shopping behavior in a simple and useful way. It gives cleaned data, analysis support, SQL queries, and a dashboard file for better business insights.
