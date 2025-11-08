# IMDB Movie Ratings Analysis of 2024

## Overview
This project explores a dataset of popular movies, focusing mainly on Indian cinema. The data includes movie titles, their runtime, IMDB ratings, and the number of reviewers.  
Through Python-based analysis, the project demonstrates sorting/filtering by popularity and rating, data visualization, and key insights extraction. This shows what factors make a movie popular among viewers.

## Data Source
- The dataset was collected by scraping movie information from [IMDB](https://www.imdb.com/search/title/?title_type=feature&release_date=2024-01-01,2024-12-31&languages=ta).
- Python libraries Requests and Selenium were used to automate extraction. Selenium handles scrolling to load all 270 movies.

## Steps Performed
- Imported and cleaned data using Pandas
- Sorted and analyzed key columns (review count, ratings)
- Visualized data with Matplotlib/Seaborn
- Exported outputs (tables as CSV, plots as PNG)
- Documented findings and insights

## How to Run
1. Install dependencies:
- For Jupyter Notebook:
  ```
  pip install notebook
  ```
- For Selenium: Download ChromeDriver (or other browser driver).

2. Download/copy project files.
3. Run `Myproject.ipynb` (Jupyter Notebook) or main Python script.
- Generates and saves cleaned CSV data and plot images.

## Key Results/Insights
- Top Ten Movies Based On Count Of Reviewers

| Title                 | RunTime | IMDB Rating | Count of Reviewers |
|-----------------------|---------|-------------|--------------------|
| Maharaja              | 141     | 8.3         | 76,000             |
| Mahavatar Narsimha    | 130     | 8.7         | 42,000             |
| Vettaiyan             | 163     | 6.9         | 41,000             |
| Manjummel Boys        | 135     | 8.2         | 31,000             |
| Merry Christmas       | 144     | 6.9         | 30,000             |
| The Greatest Of All Time | 183  | 5.7         | 25,000             |
| Amaran                | 167     | 8.1         | 22,000             |
| Meiyazhagan           | 177     | 8.4         | 20,000             |
| Viduthalai Part       | 170     | 7.7         | 18,000             |
| Indian                | NaN     | 3.8         | 17,000             |

- Most reviewers rated **Maharaja** the highest (`8.3` rating, `76,000` reviewers).
- Visualization shows the relationship between review count and rating.
- Interesting insight: Movies with 9+ ratings often have fewer reviewers than those rated between 7 and 8.

## Sample Output Files
- [plot1.png](plots/plot1.jpg) and [plot2.png](plots/plot2.jpg): Visualizations (see `/plots` folder)
- [Myproject.ipynb](Myproject.ipynb): All code and detailed steps

## Tools/Libraries Used
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Requests
- Selenium

## Author
- Muralidhara S

## Contact
- murali272004@gmail.com
