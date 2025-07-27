# Web Scraping & Data Handling Challenge

This project demonstrates how to scrape movie and TV show data from [JustWatch](https://www.justwatch.com/in/movies?release_year_from=2000) using Python. It covers web scraping, data cleaning, filtering, analysis, and exporting results for further use.

## Features

- **Scraping:** Gathers movie and TV show details (title, year, genres, IMDb rating, streaming services, URL, etc.).
- **Filtering:** Keeps only recent (last 2 years) and highly-rated (IMDb 7+) titles.
- **Analysis:** Computes average ratings, top genres, and most frequent streaming services.
- **Export:** Saves filtered data to CSV for further processing.

## Repository Contents

- `Assignment_Numerical_Programming_in_Python_Web_Scraping.ipynb` — The original Colab notebook.
- `scrape_justwatch.py` — Python script version of the scraping and analysis.
- `requirements.txt` — List of required Python libraries.
- `.gitignore` — Files and folders to exclude from version control.
- Sample outputs: `movie.csv`, `tv.csv` (generated when running the script).

## Usage

1. **Clone the Repository**

   ```bash
   git clone https://github.com/YOUR-USERNAME/justwatch-web-scraping.git
   cd justwatch-web-scraping
   ```

2. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Scraper**

   ```bash
   python scrape_justwatch.py
   ```

   This will generate `movie.csv` and `tv.csv` with the filtered data.

4. **Jupyter Notebook**

   You can also open and run `Assignment_Numerical_Programming_in_Python_Web_Scraping.ipynb` in Google Colab or locally.

## Example Dataset

See CSV outputs in [this Google Drive folder](https://drive.google.com/drive/folders/1cYQBrVvTwezfpCJvexvyPKZDFYvwCasP?usp=sharing).

## Disclaimer

- This project is for educational purposes.
- Scraping should respect website terms of service.
- Adapt the script if JustWatch changes their HTML or uses dynamic content.

---

**By Ayush245101**