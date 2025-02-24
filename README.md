# Movie_Project
## Movie Data Extraction, Cleaning, and Analysis
### Overview
This project involves extracting data from the TMDB website using their API to gather information about movies. Additionally, I downloaded data about the cast and crew of the movies. The extracted data is then cleaned by deserializing JSON data, removing duplicates, and handling missing values. Finally, the cleaned data is merged into a single dataframe by joining the movie dataframe with the cast and crew data using a common identifier and, doin explanatory data analysis and save in database.
### Features
    • Data Extraction: Utilizes TMDB API to fetch movie information.

    • Additional Data Download: Downloads information about the cast and crew of the movies.

    • Data Cleaning: Deserializes JSON data, removes duplicates, and handles missing values.

    • Data Integration: Merges the cleaned movie data with cast and crew data based on common identifiers.

    • Explanatory Data Analysis (EDA):

        ◦ Identifies the best and worst movies based on budget, revenue, rating, votes, and popularity.

        ◦ Searcheing for movies based on specific criteria, e.g., recommendations for movies to watch next.

        ◦ Finding the most successful directors and actors.



### Requirements
    • Python 3.x

    • Pandas, Matplotlib

    • TMDB API Access (API Key required)

### Installation
  
    1- Obtain an TMDB API Key from TMDB API.

    2- Add your TMDB API Key to the configuration file.

### Usage
    1. Set up your TMDB API Key.

    2. Run the data extraction script to fetch movie information.

    3. Run the data download script to obtain cast and crew data.

    4. Run the data cleaning script to clean the extracted data.

    5. Run the data integration script to merge the cleaned data.

    6. Perform Explanatory Data Analysis (EDA) to:

        ◦ Identify the best and worst movies based on various criteria (budget, revenue, rating, votes, and popularity).

        ◦ Search for movies based on specific criteria.(what would you like to watch )

        ◦ Identify the most successful directors and actors.

    7. Analyze the integrated data for further insights.
    
    8. Saving in database sqlite.

