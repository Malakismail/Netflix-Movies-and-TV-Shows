## Netflix Movies and TV Shows Analysis

![BrandAssets_Logos_01-Wordmark](https://github.com/user-attachments/assets/ba39ef02-e481-491f-b4e9-740ab321ef99)

**Project Overview**

This project performs an in-depth Exploratory Data Analysis (EDA) of the Netflix Movies and TV Shows dataset. The analysis focuses on understanding the content distribution, identifying trends, and generating insights to assist producers, content creators, and Netflix decision-makers. Key objectives include analyzing movie vs. TV show distribution, determining optimal release months, and identifying top-rated movies and their origins.

## Dataset

**Source**

The dataset is publicly available and contains information about movies and TV shows on Netflix, including:
•	Titles
•	Directors
•	Cast
•	Release Year
•	Date Added to Netflix
•	Ratings
•	Duration
•	Country of Production
•	Genres ("Listed In")

**Preprocessing Steps**
1.	Handling Missing Values:
o	Imputed or cleaned missing values for key columns such as rating and date_added.
o	Adjusted misplaced data (e.g., durations misclassified as ratings).
2.	Feature Engineering:
o	Extracted year, month, and period from date_added.
o	Split multi-value columns (cast, director, country, listed_in) into separate entries for granular analysis.
3.	Data Cleaning:
o	Removed invalid or empty entries in key columns.
o	Converted categorical columns (type, rating) to appropriate data types.

## Analysis Goals
1. Movies vs. TV Shows
•	Distribution and trends over the years.
•	Insights into the type of content dominating Netflix’s catalog.
2. Optimal Release Timing
•	Analyzed the date_added column to determine the best months for releasing new content based on historical trends.
3. Top-Rated Movies
•	Leveraged IMDB ratings to identify the highest-rated movies available on Netflix.
•	Extracted the top 10 content-producing countries based on movie quality.
4. Directors and Cast Analysis
•	Identified the most prolific directors for movies and TV shows.
•	Explored actor appearances across the platform.
5. Genre Analysis
•	Examined popular genres ("listed_in") and their distribution.

## Visualizations

**Key Insights Presented**
1.	Top Directors:
o	Bar plots showing the most frequent directors for movies, TV shows, and combined categories.
2.	Movies and TV Shows Over Time:
o	Line charts illustrating the growth of Netflix’s catalog over the years.
3.	Country Contributions:
o	Pie and bar charts visualizing content contributions by country.
4.	Monthly Release Trends:
o	Heatmaps and bar charts depicting seasonal content addition patterns.

**Tools Used**
•	Matplotlib and Seaborn for creating detailed and interactive plots.
•	Grid-based layouts for comparing visualizations effectively.

## Technologies Used
•	Python
o	Libraries: Pandas, Numpy, Matplotlib, Seaborn, Datetime
•	Jupyter Notebook for scripting and analysis.

## Future Improvements
•	Incorporate machine learning models to predict trends in Netflix content.
•	Analyze additional datasets (e.g., user ratings, viewership stats).
•	Create a dashboard for real-time data visualization.

## Contributing
Contributions are welcome! Fork the repository, create a branch for your feature or bug fix, and submit a pull request.

## Contact
For inquiries or collaboration opportunities, please reach out to me:

**Name**: Malak Ismail  

**Email**: malakismail706@gmail.com 

**LinkedIn**: https://www.linkedin.com/in/malakismail0/

