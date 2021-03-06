# Individual Brainstorming

## Matt:

[Africa Economic, Banking and Systemic Crisis Data](https://www.kaggle.com/chirin/africa-economic-banking-and-systemic-crisis-data)

Look at the relationship between Banking, Debt, Financial, Inflation and Systemic Crises.
* 13 African countries
* 1860-2014

[Facebook Data](https://www.kaggle.com/sheenabatra/facebook-data)

Use number of likes as the dependent variable and see how things like DOB month, DOB year, friends, etc. affect it.
* 99,903 x 15

[Spotify - All Time Top 2000s Mega Dataset](kaggle.com/iamsumat/spotify-top-2000s-mega-dataset)

See if there is any commonality among the top 2000 tracks on Spotify
* songs released from 1956-2019
* 15 columns each describing the track
* 1995 observations

## Logan: 

[College Football Data](https://github.com/saiemgilani/cfbscrapR)

R package which draws college football data from ESPN API. Can answer questions dealing with various subjects, from on-field play to betting data to recruiting. (there is also an nfl version)

[Stock Market Prediction](https://www.kaggle.com/aaron7sun/stocknews)

Research how daily news can affect stock prices.

[Kepler Exoplanet Search Data](https://www.kaggle.com/nasa/kepler-exoplanet-search-results)

Look at characteristics of exoplanets, see if we can find relationships. 

## Sarah:

[Health Nutrition and Population Statistics](https://www.kaggle.com/theworldbank/health-nutrition-and-population-statistics)

* Includes key health, nutrition and population statistics
* Contains data from 1960 - 2015
* 258 countries (would be able to join with other data sets with country as unti of analysis if we wanted to pull in other information)

Personally, I am interested in looking at health indicators versus access to healthcare and physicians.

[Sleep Deprivation](https://www.kaggle.com/feraco/sleep-deprivation?select=demdata_160225_pseudonymized.csv)

* Study of 86 Individuals with sleep and health related data

What type of phisycal and mental health factors affect quality of sleep?

## Meena:

[Netflix movies and TV Shows](https://www.kaggle.com/shivamb/netflix-shows)

This dataset consists of tv shows and movies available on Netflix as of 2019. Motivating question for this data set would be : Is netflix focusing on TV rather than movies in recent years!? We can integrate this with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

[Best Artworks of all time](https://www.kaggle.com/ikarus777/best-artworks-of-all-time)

Collection of best artworks of 50 most popular artists from wikipedia.

[Glassdoor Job Postings : Data Science](https://www.kaggle.com/atharvap329/glassdoor-data-science-job-data)

There are job lisitng for Data Scientist and related roles. The job listings are scraped from Glassdoor.co.in and lot of analysis hasn't been done in Kaggle with the data set which makes it easier for us to explore the data set.

# Group Discussion

We met as a group as narrowed down our search to the follow candidates in no specific order.

## 1. [Sleep Deprivation](https://www.kaggle.com/feraco/sleep-deprivation?select=demdata_160225_pseudonymized.csv)

**Description:** This dataset is from a study done on sleep deprivation. It includes physical and mental health related data points on individuals that participated in the study as well as detailed data on their brain function while sleeping.

* Dimensions - There are two datasets, one with health realted information and answers to survey questions from the participants that is 90 rows with 106 columns    and the other datset is about participants brain function while sleeping which is 86 rows with 80 columns. Each participant was assigned a unique id so these datasets could easily be joined.

* Unit of Analysis - an individual person partaking in the study.

**Motivating Questions:** What physical and mental factors affect an individual's quality of sleep? How much do these factors affect sleep quality?

## 2. [College Football Data](https://github.com/saiemgilani/cfbscrapR)

**Description:** This R pcakage contains several college football datasets, collected via ESPN's API: betting lines, coaches, conferences, play-by-play results, game results, team records, win probability data, predicted points data, player information, team ratings and rankings, recruiting data, advanced statistics, roster data, team travel data, team venue data, and more. This provides virtually endless possibilities for research, which will allow for thorough analysis in whichever topic we chose for our project. 

**Motivating Questions:** Which schools excel in recruiting? Are there certain areas of the country that are better to recruit from? Do certain schools perform better in certain areas of the country? Does distance play a factor in recruiting? How does recruiting relate to on-field performance? Do certain coaches/conferences/schools excel in recruiting? 

* Dimensions - Player recruiting data for year 2020: 3936 observations of 14 columns (data extends back to 2000, so all years would be 20 times the amount of observations). Additionally has the potential to be merged with other datasets depending on motivating questions.

* Unit of Analysis - For 2020 player recruiting data: individual high school recruit. 

## 3. [Spotify - All Time Top 2000s Mega Dataset](https://www.kaggle.com/iamsumat/spotify-top-2000s-mega-dataset)

**Description** This dataset contains audio statistics of the top 2000 tracks on Spotify and it contains songs released from 1956 to 2019. This data contains audio features like Danceability, BPM, Liveness, Valence(Positivity) and many more.

* Dimensions - There are 2000 observations with 15 columns.

* Unit of Analysis - features of a song

**Motivating Questions:** I am interested in finding which genres were most popular during this time frame and we could also find a popular genre within decades.


## 4. [Glassdoor Job Postings : Data Science](https://www.kaggle.com/atharvap329/glassdoor-data-science-job-data)

**Description** This is a scrapeddata set related to the position of 'Data Scientist' from glassdoor.com for selected states of California,Washington,New York as major areas to find the roles. The main motive behind this dataset was to look at which companies were still hiring individuals,where were they located,what kind of salary they were giving and what kind of individuals they are looking to hire.

**Motivating question** What's the minimum and maximum salary offered for various job titles related to data science?

**Dimensions** It has 2000 observations from 12 columns. (There are 4 csv files which can be merged)

**Unit of analysis** The unit of analysis is the the yearly salary in USD.
