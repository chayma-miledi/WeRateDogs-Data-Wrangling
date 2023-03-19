# WeRateDogs-Data-Wrangling
This project aims to wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations. 
WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. The WeRateDogs Enhanced Twitter archive contains basic tweet data for all 5000+ of their tweets as they stood on August 1, 2017.

## Data Gathering
The data was gathered from 3 sources:

1. WeRateDogs Twitter Enhanced archive, manually downloaded from the Udacity servers.
2. The image predictions file, programmatically downloaded from the Udacity servers.
3. The entire set of each tweets’ JSON data, downloaded by querying the Twitter API using the Tweepy library from where I extracted the favorite_count and retweet_count.
Technologies Used

## Project Implementation
The project was implemented using Jupyter Notebook with the following Python libraries:

Pandas for data manipulation and analysis
NumPy for numerical operations
Requests for accessing and downloading data from web pages
Tweepy for accessing Twitter API
Matplotlib and Seaborn for data visualization

## Repository Contents
This GitHub repository contains the following files:

* WeRateDogs Data Wrangling.ipynb: Jupyter notebook containing the data wrangling process.
* wrangle_report.pdf: Data wrangling report explaining the process of gathering, assessing, and cleaning the data.
* act_report.pdf: Findings report explaining the insights and visualizations obtained from the cleaned data.
* image-predictions.tsv: Tab-separated file containing the dog breed predictions from neural network algorithm.
* tweet_json.txt: Text file containing the JSON data obtained from querying Twitter API.
* twitter_archive_master.csv: CSV file containing the cleaned data after wrangling.

## Usage
To use this project, clone the GitHub repository to your local machine and run the Jupyter notebook WeRateDogs Data Wrangling.ipynb to reproduce the data wrangling process. 
The cleaned data can be found in twitter_archive_master.csv and can be used for further analysis and visualization.

Conclusion
This project provides a comprehensive analysis of WeRateDogs Twitter data through the process of data wrangling, analysis, and visualization. The cleaned data provides valuable insights into the popularity of different dog breeds, the relationship between retweets and favorites, and the most common dog names. This project serves as a valuable resource for anyone interested in dog-related data analysis or social media analysis in general.
