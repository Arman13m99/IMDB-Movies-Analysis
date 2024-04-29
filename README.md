# IMDB Movie Dataset Analysis

## Overview
This notebook explores a dataset containing information about movies, including various attributes such as title, release date, genres, budget, revenue, and more. The aim is to conduct initial data exploration, filtering, and identify top and bottom performers based on different criteria.

## Dataset Description
The dataset includes the following columns:

- **id:** The ID of the movie (clear/unique identifier).
- **title:** The Official Title of the movie.
- **tagline:** The tagline of the movie.
- **release_date:** Theatrical Release Date of the movie.
- **genres:** Genres associated with the movie.
- **belongs_to_collection:** Gives information on the movie series/franchise the particular film belongs to.
- **original_language:** The language in which the movie was originally shot in.
- **budget_musd:** The budget of the movie in million dollars.
- **revenue_musd:** The total revenue of the movie in million dollars.
- **production_companies:** Production companies involved with the making of the movie.
- **production_countries:** Countries where the movie was shot/produced in.
- **vote_count:** The number of votes by users, as counted by TMDB.
- **vote_average:** The average rating of the movie.
- **popularity:** The Popularity Score assigned by TMDB.
- **runtime:** The runtime of the movie in minutes.
- **overview:** A brief blurb of the movie.
- **spoken_languages:** Spoken languages in the film.
- **poster_path:** The URL of the poster image.
- **cast:** (Main) Actors appearing in the movie.
- **cast_size:** number of Actors appearing in the movie.
- **director:** Director of the movie.
- **crew_size:** Size of the film crew (incl. director, excl. actors).

## Analysis
The notebook performs the following tasks:

1. Data Import and Initial Inspection: Loading the dataset and examining its structure and contents.
2. Data Filtering: Filtering the dataset based on specific criteria.
3. Identifying Top and Bottom Performers:
   - Movies with Highest Revenue
   - Movies with Highest Budget
   - Movies with Highest Profit (Revenue - Budget)
   - Movies with Lowest Profit
   - Movies with Highest Return on Investment (ROI) (Budget >= 10)
   - Movies with Lowest Return on Investment (ROI) (Budget >= 10)
   - Movies with Highest Number of Votes
   - Movies with Highest Rating (10 or more Ratings)
   - Movies with Lowest Rating (10 or more Ratings)
   - Movies with Highest Popularity

## Requirements
- Python 3.9.18
- Jupyter Notebook
- Required Python libraries (pandas, numpy, matplotlib, seaborn, wordcloud, IPython)

## Usage
1. Clone the repository to your local machine.
2. Navigate to the directory containing the notebook.
3. Launch Jupyter Notebook.
4. Open the notebook `movie_analysis.ipynb`.
5. Follow the instructions and run each cell to execute the analysis steps.

