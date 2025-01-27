# Retrieve Movie Data from APIs

## Overview

This Jupyter notebook demonstrates how to retrieve and merge movie data from two different APIs: the New York Times (NYT) API and The Movie Database (TMDb) API. The notebook covers importing required libraries, setting up environment variables, accessing the APIs, and merging the retrieved data for export.

Structure

1. Import Required Libraries and Set Up Environment Variables
The notebook begins by importing necessary libraries such as requests, pandas, and dotenv. It then loads environment variables from a .env file to securely access API keys.

2. Access the New York Times API
This section details how to interact with the NYT API to search for movie reviews with specific criteria. The criteria include filtering for movie reviews with "love" in the headline, sorting by newest, and selecting specific fields to return.

3. Access The Movie Database API
This section involves accessing the TMDb API to retrieve additional movie data. The API key and other configurations are set up to make requests to the TMDb API.

4. Merge and Clean the Data for Export
Finally, the notebook merges data from both APIs and cleans it for further analysis or export. This includes handling missing data, normalizing formats, and ensuring consistency across the datasets.

## Usage

1. Clone the repository:

```python
git clone <repository-url>
Navigate to the project directory:
```

2. Navigate to the project directory:
  ```python
  cd <project-directory>
 
  ```
3. Install required dependencies:

4.  Set up environment variables:
    . Create a .env file in the project root directory.
    . Add your NYT and TMDb API keys to the .env file:

 ```python
  NYT_API_KEY=your_nyt_api_key
  TMDB_API_KEY=your_tmdb_api_key
```

5. Run the Jupyter notebook:
  ```python
  jupyter notebook retrieve_movie_data.ipynb
```
6. Execute the cells in the notebook to retrieve, merge, and clean the movie data.

## Notes

1. Ensure you have valid API keys for both the New York Times and The Movie Database before running the notebook.
2. The notebook assumes a basic familiarity with Python and Jupyter notebooks.
