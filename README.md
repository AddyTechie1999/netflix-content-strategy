<h1>Netflix Content Strategy Analysis Portfolio Project</h1>

<h2>📌 Project Overview</h2>
This project explores the Netflix Movies & TV Shows dataset using Python. The goal is to understand content distribution, trends, data quality issues, and patterns that can support data-driven decisions for content strategy.
The workflow includes data loading, cleaning, EDA, feature engineering, and visualizations using Matplotlib and Seaborn.

<h2>📂 Dataset</h2>

- Dataset: Netflix Movies and TV Shows
- Rows : 8807
- Format: CSV
- Contains information such as:<br/>
  *	Show ID
  *	Type (Movie / TV Show)
  *	Title
  *	Director & Cast
  *	Country
  *	Date Added
  *	Release Year
  *	Rating
  *	Duration
  *	Genre (Listed In)


<h2>🛠️ Tools & Technologies</h2>

* Programming: Python
* Libraries: Pandas, NumPy, Matplotlib, Seaborn
* Environment: Jupyter Notebook / VS Code

<h2>🔄 Project Steps</h2>

1. Data Loading<br/>
   *	Imported dataset using pandas.read_csv()
   *	Checked basic structure with .head(), .info(), .describe()

2. Data Cleaning & Transformation<br>
   *	Handled missing values
   *	Standardized categorical fields (e.g., country, director)
   *	Cleaned date column and converted to datetime
   *	Removed duplicates
   *	Extracted year/month fields for deeper analysis

3. Feature Engineering<br/>
   * 

4. Exploratory Data Analysis (EDA)<br/>
   *	Analyzed distributions of Movies vs TV Shows
   *	Examined content growth over years
   *	Studied ratings, genres, and country-wise availability
   *	Identified missing values and inconsistencies

4. SQL Analysis (MySQL)<br>
   *	Loaded cleaned data into MySQL
   *	Wrote SQL queries to answer key business questions
   *	Used filtering, aggregation, CTEs and subqueries

5.  Dashboard Development (Power BI)<br>
    *	Designed an interactive dashboard
    *	Visualized KPIs and trends

6. Reporting & Presentation<br>
   *	Created a structured analytical report
   *	Designed a Gamma presentation to communicate insights clearly to business stakeholders

<h2>📊 Power BI Dashboard</h2>

The dashboard highlights:<br/>
*	Movies vs TV Shows comparison
*	Year-wise content growth on Netflix
*	Top genres and ratings
*	Country-wise content distribution
  
<h2>📈 Key Results & Insights</h2>

*	Netflix’s content library has grown significantly over recent years
*	Movies dominate Netflix’s library compared to TV Shows
*	Certain genres and ratings consistently appear more frequently
*	Content availability varies significantly by country
*	Recent years show a stronger focus on original and diverse content
