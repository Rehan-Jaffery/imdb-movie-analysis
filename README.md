# IMDB Movie Data Analysis

## Project Overview
This project presents an exploratory data analysis (EDA) of a comprehensive IMDB movie dataset. As a Data Analyst, my objective was to uncover actionable insights for a hypothetical movie studio aiming to maximize both Box Office Gross and audience Ratings.

## Business Questions Answered
- Does movie duration impact audience ratings?
- Which genres are the most profitable? Which have the highest average ratings?
- Who are the most consistently successful directors (highest hit rate vs. highest total gross)?
- What is the effect of film certification (e.g., PG-13, R) on revenue?
- How much does the "Sequel Effect" (movies with numbers in their titles) influence earnings?
- Finding "Hidden Gems" (high rating, low box office) and "Overhyped Movies" (low rating, high box office).

## The Ultimate Business Decision
Based on the data, the optimal strategy for a movie studio looking to maximize Box Office Gross and Rating:
1. **Director**: Hire Steven Spielberg (Highest total gross) or Christopher Nolan (High hit rate).
2. **Actors**: Cast Nicolas Cage (most experienced/frequent) or pair a known successful duo.
3. **Genre**: Action/Adventure/Comedy (high gross) or Animation (highest rated).
4. **Certificate**: PG-13 (hits the sweet spot of wide audiences and high grossing averages).
5. **Franchise**: Add a number to the title! Sequels make significantly more money on average.

## Project Structure
```
├── data/
│   └── raw/
│       └── movies.csv               <- The dataset used for analysis
├── notebooks/
│   └── 01-exploratory-data-analysis.ipynb <- Jupyter notebook with all code and visualizations
├── reports/
│   └── imdb_analysis_report.pdf     <- Exported report of the analysis
├── .gitignore
├── README.md                        <- Project documentation
└── requirements.txt                 <- Python dependencies
```

## Tech Stack
- **Python** (Pandas, NumPy)
- **Data Visualization** (Matplotlib, Seaborn)
- **Data Profiling** (YData Profiling)
- **Jupyter Notebooks**

## How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone <your-github-repo-url>
   cd "Imdb Project"
   ```

2. **Install dependencies:**
   It is recommended to use a virtual environment.
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebook:**
   ```bash
   jupyter notebook notebooks/01-exploratory-data-analysis.ipynb
   ```

## Contact
Connect with me on [LinkedIn](https://www.linkedin.com/in/) or view my portfolio at [GitHub](https://github.com/).
