# Netflix Data Analysis

This project focuses on cleaning and analyzing Netflix data to extract meaningful insights. The dataset contains various details about Netflix movies and TV shows such as title, director, cast, country, date added, rating, duration, and listed categories.

## Data Preprocessing

The initial dataset contains missing values and combined columns for cast, listed categories, and countries. The preprocessing steps include:

1. **Importing Libraries and Data**:
   - Libraries: `pandas`, `numpy`, `seaborn`, and `matplotlib`.
   - Data: Read from `data_netflix_fix.csv`.

2. **Data Cleaning**:
   - Replacing missing values in the 'director', 'cast', and 'country' columns with 'Unknown'.
   - Dropping rows with missing values in the 'date_added', 'rating', and 'duration' columns.

3. **Data Transformation**:
   - Splitting the 'cast', 'listed_in', and 'country' columns into separate rows.
   - Stripping whitespace from 'cast', 'listed_in', and 'country' values.

4. **Exporting Cleaned Data**:
   - Saving the processed DataFrame to `netflix_titles_processed.csv`.

## Files in the Repository

- `data_netflix_fix.csv`: Original dataset.
- `netflix_titles_processed.csv`: Cleaned and transformed dataset.
- `netflix_data_analysis.ipynb`: Jupyter notebook containing the data cleaning and transformation code.
- `README.md`: This file.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/netflix-data-analysis.git
