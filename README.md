US Company Financial Data Scraper and Analyzer

This project scrapes and analyzes financial and operational data of the largest U.S. companies by revenue from a Wikipedia page. It provides structured insights through data cleaning, transformation, and rich visualizations.

Overview

This project includes:

Web Scraping: Extracts company data from Wikipedia tables.
Data Cleaning: Converts string values to usable numeric formats.
Data Visualization: Shows relationships between revenue, employee count, and industry classification.
EDA: Performs Exploratory Data Analysis on real-world data.
Data Source

Wikipedia Page: List of largest companies in the United States by revenue

Extracted Data Fields:

Rank: Position in the revenue ranking
Name: Company name
Industry: Sector in which the company operates
Revenue (USD billions)
Revenue growth
Employees
Headquarters
⚠Note: Columns such as Employees and Revenue are cleaned and converted to numerical types for analysis.

Technologies Used

Category	Libraries/Tools
Web Scraping	requests, BeautifulSoup
Data Manipulation	pandas
Visualization	matplotlib, seaborn
Environment	Jupyter Notebook (.ipynb)
Installation

Make sure you have Python 3.6+ installed.

Install required libraries:

bash pip install requests beautifulsoup4 pandas matplotlib seaborn

How to Run Clone the repository:

git clone https://github.com/your-username/us-company-scraper.git cd us-company-scraper Open and run the notebook:

jupyter notebook "web scraping (1).ipynb" The notebook includes all steps: scraping, cleaning, and visualization.

Visualization Output This project includes multiple insightful plots:

Bar Chart – Top Companies by Revenue

Shows the top companies sorted by revenue.

Helps identify the largest revenue-generating firms.

Pie Chart – Industry Distribution

Displays the proportion of companies by industry.

Useful to understand the market spread across sectors.

Scatter Plot – Revenue vs Employees

X-axis: Number of Employees

Y-axis: Revenue (USD billions)

Color-coded by Industry

Highlights the relationship between workforce size and revenue across industries.
