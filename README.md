# Customer_bihavior_analyse
# Customer Shopping Behavior Analysis

## Project Overview
This project analyzes customer shopping behavior to identify purchasing patterns, customer segments, product performance, and subscription trends. It uses Python for data cleaning and exploratory data analysis (EDA), SQL for querying and analyzing data, and Power BI to build an interactive dashboard.

## Dataset
The project uses the `customer_shopping_behavior.csv` dataset, which contains information about customer demographics, purchased products, purchase amounts, discounts, reviews, and subscription status.

## Tools & Technologies
- **Python:** Pandas, data cleaning, and exploratory data analysis.
- **SQL:** PostgreSQL for querying and extracting business insights.
- **Power BI:** Interactive dashboards and data visualization.
- **Gamma:** Presentation slides summarizing the project findings.

## Project Workflow

1. **Data Loading:** Import the CSV dataset into Python.
2. **Data Cleaning:** Handle missing values, standardize column names, and prepare the data for analysis.
3. **Exploratory Data Analysis:** Explore customer demographics, purchasing patterns, and product categories.
4. **Database Integration:** Load the cleaned dataset into PostgreSQL.
5. **SQL Analysis:** Answer business questions about revenue, discounts, customer loyalty, product ratings, and subscriptions.
6. **Dashboard Development:** Create an interactive Power BI dashboard to visualize key performance indicators (KPIs) and insights.
7. **Reporting:** Summarize the findings in a project report and a presentation created with Gamma.

## Dashboard
The Power BI dashboard presents key metrics and visualizations, helping users understand customer purchasing behavior and identify business opportunities.

*Add a screenshot of your Power BI dashboard here.*

## Key Analysis Areas
- Revenue by gender and product category.
- Customer spending patterns and average purchase amounts.
- Discount usage and product performance.
- Customer segmentation: New, Returning, and Loyal.
- Subscription behavior and repeat purchases.
- Product ratings and purchasing preferences.

## Results & Insights
The analysis aims to identify valuable customer segments, understand the impact of discounts, compare purchasing patterns, and discover opportunities to improve customer engagement and sales.

*Add your actual findings and key metrics after completing the analysis.*

## How to Run

1. Clone or download this repository.
2. Install the required Python libraries:

   ```bash
   pip install pandas sqlalchemy psycopg2-binary
   ```

3. Place `customer_shopping_behavior.csv` in the project directory.
4. Run the Python script to clean and prepare the data.
5. Import the cleaned data into PostgreSQL.
6. Execute the SQL queries using PostgreSQL or pgAdmin.
7. Open the Power BI `.pbix` file to explore the dashboard.

## Project Structure

```text
customer-shopping-analysis/
├── data/
│   └── customer_shopping_behavior.csv
├── python/
│   └── data_cleaning.py
├── sql/
│   └── analysis_queries.sql
├── powerbi/
│   └── customer_dashboard.pbix
├── report/
│   └── project_report.pdf
├── presentation/
│   └── project_presentation.pptx
└── README.md
```

## Conclusion
This project demonstrates practical data analytics skills, from data preparation and SQL querying to interactive visualization and business reporting. It combines multiple tools to transform raw customer data into meaningful insights that support data-driven decision-making.

## Author
**Khadija Eljaouhari**

Master's student in Artificial Intelligence and Optimal Decision Systems (IASDO), interested in Data Analytics, Business Intelligence, and data-driven decision-making.
