<h1>Netflix EDA Project</h1>

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
   *	Cleaned date column and converted to datetime
   *	Removed duplicates
   *	Extracted year/month fields for deeper analysis

3. Feature Engineering<br/>
   * Extracted: Year Added, Month Added, Number of Cast Members, Primary Genre, Movie Duration (minutes) and TV Show Seasons
   * Created new columns to support trend analysis

4. Exploratory Data Analysis (EDA)<br/>
   *	Analyzed distributions of Movies vs TV Shows
   *	Trend of content added over years
   *	Studied ratings, genres, and country-wise availability
   *	Relationship between duration and content type

5. Visualization<br/>
   * Created clear and meaningful charts using Matplotlib & Seaborn, including:
     * Pie charts for content type distribution
     * Count plots for ratings and TV Show Seasons distribution
     * Line plots for trends of content added over time
     * Bar plots for countries and genres
     * Histograms for movie duration (minutes) distribution
     * Heatmaps for correlations
  
<h2>📈 Key Insights</h2>

  * Movies dominate Netflix’s library, making up the majority of total titles compared to TV Shows.
  * United States and India are the top content-producing countries on Netflix, contributing the highest number of titles.
  * There was exponential growth in content addition between 2015–2019, before showing a slight decline in 2020, possibly due to COVID-19 production impacts.
  * TV-MA and TV-14 are the most common ratings, suggesting that Netflix’s library is heavily geared toward mature and teen audiences.
  * International Movies, Dramas and Comedies are the most frequent genres,, reflecting Netflix’s global expansion along with its focus on mature storytelling and real-life themes.
  * Typical movie duration ranges between 90–100 minutes, aligning with standard feature film lengths.
  * TV Shows usually have 1 season, indicating either a preference for limited series or cancellation of such shows by Netflix.
  * Most content appears to be released in July/August which aligns with summer break and December which aligns with Christmas/New Year's Eve to maximize binge-watching hours.
  * Overall, the data shows Netflix’s strategic focus on producing more movies, diversifying international content and catering primarily to adult audiences.
