# Web Scraping on Movies Website Using Python

This Python script scrapes movie data from The Movie Database (TMDb) website and stores it in an Excel file for further analysis or reference. Here's an overview of its key functionalities:

1) **Scraping Movie Information:**
    * Utilizes the requests library to fetch data from TMDb website.
    * Parses HTML content using BeautifulSoup.
    * Iterates through multiple pages of movies (up to 25) to gather information.
  
2) **Data Extracted:**
    * Extracts movie name, rating, genre, release date, runtime, and director name.
    * Handles cases where certain information (like runtime) might be unavailable.
  
3) **Data Structuring:**
    * Organizes extracted data into a dictionary for each movie.
    * Appends each movie dictionary to a list to store all movie information.
  
4) **Data Storage:**
     *Transforms the list of dictionaries into a pandas DataFrame for easier manipulation.
     * Outputs the DataFrame to an Excel file named "Movie_data.xlsx".
  
5) **GitHub Repository Integration:**
    * Designed for uploading to a GitHub repository.
    * Provides a comprehensive README file explaining the script's purpose, usage, and any prerequisites.
