# IMDB-movie-data-scraper
A Python project that scrapes IMDb's Top 250 movies using BeautifulSoup, Selenium, and Pandas. It extracts details like title, year, runtime, rating, reviews, summary, genres, director, and cast. The data is structured into a CSV for analysis, enabling insights into trends and movie details.

---

## Features  

The script scrapes and extracts the following information for each movie:  
- **Title**: The name of the movie.  
- **Release Year**: Year of release.  
- **Runtime**: Duration of the movie.  
- **Censorship Rating**: Age rating or content advisory.  
- **IMDb Rating**: Average user rating.  
- **Number of Ratings**: Total number of user ratings.  
- **Reviews**: Textual reviews for each movie.  
- **Summary**: Plot or storyline description.  
- **Tags/Genres**: Categories or genres of the movie.  
- **Director**: Name of the director.  
- **Cast**: Names of lead actors or cast members.  

---

## Tech Stack  

This project uses the following Python libraries:  
1. **BeautifulSoup** - For parsing and navigating the IMDb HTML content.  
2. **Selenium** - For automating browser interactions and handling dynamic content.  
3. **Pandas** - For organizing, cleaning, and exporting the scraped data.

---

## Installation and Setup  

### Prerequisites  
- Python 3.7 or higher  
- Web driver for Selenium (e.g., ChromeDriver for Google Chrome)  
- Required Python libraries: `beautifulsoup4`, `selenium`, `pandas`

### Steps  
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/imdb-top250-scraper.git
   cd imdb-top250-scraper

