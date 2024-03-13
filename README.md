# Behind the Curtain: Statistical Insights into Movie Success

This project aims to unveil the factors contributing to the success of movies, as judged by audience ratings. Utilizing a dataset encompassing a variety of films, this analysis employs Generalized Linear Models (GLM) to understand how different attributes—such as length, budget, genre, and viewer engagement—impact the likelihood of a film achieving a rating above 7.

## Project Structure

- `data/`: Contains the dataset used in the analysis.
- `scripts/`: R scripts and R Markdown files for data preprocessing, exploratory data analysis (EDA), and statistical modeling.
- `outputs/`: Generated reports and visualizations in HTML or PDF format.
- `README.md`: This file, providing an overview of the project and instructions for replication.

## Data Description

The dataset includes the following variables for each film:

- `film_id`: Unique identifier
- `year`: Year of release
- `length`: Duration in minutes
- `budget`: Production budget in million dollars
- `votes`: Number of positive votes received
- `genre`: Film genre
- `rating`: IMDb rating from 0-10
