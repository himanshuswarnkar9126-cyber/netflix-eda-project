# Netflix Movies and TV Shows — Exploratory Data Analysis

## Project Overview
This project explores Netflix Movies and TV Shows data using Python to identify content trends, understand the catalog, and discover patterns in Netflix's content distribution.

## Objectives
- Analyze Movies vs TV Shows distribution.
- Explore content additions over time.
- Identify leading countries and popular genres.
- Analyze content ratings and movie durations.
- Explore Indian content and its trends.
- Handle missing values and clean data for reliable analysis.

## Dataset
The project uses the **Netflix Movies and TV Shows** dataset, containing information such as title, content type, director, cast, country, release year, rating, duration, genre, and description.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow
1. Data loading and understanding
2. Data quality checks
3. Data cleaning and preprocessing
4. Feature engineering
5. Exploratory data analysis
6. Visualizations and insights

## Key Analysis Areas
- Content type distribution
- Content added by year and month
- Country-wise content distribution
- Genre analysis
- Ratings analysis
- Movie duration and TV Show seasons
- Indian content analysis

## How to Run
1. Clone or download this repository.
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Keep `netflix_titles.csv` in the same folder as the notebook.
4. Open `Netflix_EDA_Final.ipynb` in Jupyter Notebook.
5. Run the notebook cells.

## Project Structure
```text
netflix-eda-project/
├── Netflix_EDA_Final.ipynb
├── netflix_titles.csv
├── README.md
└── requirements.txt
```
## Key Findings

- **Content Distribution:** Movies significantly outnumber TV Shows in the Netflix dataset, with approximately 6,100 Movies compared with 2,700 TV Shows.
- **Content Addition Trends:** Netflix content additions increased sharply from 2016 onward and peaked in 2019 at approximately 2,000 titles. The yearly additions declined after 2019.
- **Popular Genres:** International Movies is the most frequently listed genre, followed by Dramas and Comedies.
- **International Content:** International Movies and International TV Shows both feature among the top 10 listed categories, highlighting the variety of content represented in the catalog.

## Insights and Interpretation

The analysis shows that Movies make up the larger share of the catalog. Content additions rose rapidly during the late 2010s, while international content, dramas, and comedies are prominent categories in the dataset.

*Note: Genre counts may include the same title in multiple categories. The yearly trend reflects the dataset's recorded addition dates, not Netflix's total global releases in each year.*

## Conclusion
This project demonstrates data cleaning, feature engineering, exploratory analysis, and visualization techniques using a real-world entertainment dataset.

---
**Created as a Python Data Analytics project.**
